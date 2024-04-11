<script>
export default {
    name: 'AppServices'
}
</script>

<template>
<div class="nav-wrapper">
  <nav>
    <ul>
      <li>
        <a href="#">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
          <span>DIGITAL COMICS</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/img/buy-comics-merchandise.png" alt="DC Merchandise">
          <span>DC MERCHANDISE</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
          <span>SUBSCRIPTION</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="Comic Shop Locator">
          <span>COMIC SHOP LOCATOR</span>
        </a>
      </li>
      <li>
        <a href="#">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="DC Power Visa">
          <span>DC POWER VISA</span>
        </a>
      </li>
    </ul>
  </nav>
</div>
</template>

<style scoped lang="scss">
.nav-wrapper {
  background-color: #0072bc;
  padding: 45px 20px; 
}

nav ul {
  list-style-type: none;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 40px;
}

nav li {
  margin: 0 10px;
  display: flex;
  align-items: center;
}

nav a {
  display: flex;
  align-items: center;
  text-decoration: none;
  color: white;
}

nav img {
  height: 50px;
  margin-right: 5px;
}

nav span {
  font-size: 14px;
}
</style>