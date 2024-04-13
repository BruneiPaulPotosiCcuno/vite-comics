<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
<header>
    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="Logo">
    </div>
    <nav>
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIVES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped lang="scss">

@use '../style/partials/variables' as *;


header {
  position: fixed;
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 20px;
  background-color: #ffffff;
  font-size: 17px;
}

.logo img {
  width: 80px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav ul li {
  margin-left: 20px; 
}


nav ul li a {
  text-decoration: none;
  color: $brand_secondary;
}

a:hover{
    color: $brand_primary;
}

</style>