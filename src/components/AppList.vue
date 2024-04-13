<script>
export default {
    name: 'AppList'
}
</script>

<template>
<div class="nav-container">
  <nav>
    <div class="nav-left">
      <div class="nav-columns">
        <div class="nav-column">
          <div class="nav-title">DC COMICS</div>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <div class="nav-title">SHOP</div>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="nav-column">
          <div class="nav-title">DC</div>
          <ul>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div class="nav-column">
          <div class="nav-title">SITES</div>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="nav-right">
      <div class="logo">
        <a href="#"><img src="../assets/img/dc-logo-bg.png" alt="Logo"></a>
      </div>
    </div>
  </nav>
  
</div>
</template>

<style scoped  lang="scss">
.nav-container {
  background-image: url('../assets/img/footer-bg.jpg');
  color: #fff;
  height: 350px;
}

nav {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  
}
.nav-right img{
    height: 500px;
    padding-left: 100px;
    position: relative;
    bottom: 55px;
    
}

.nav-right{
    overflow: hidden;
}
.nav-left {
  margin-right: 100px;
  padding: 30px;
}

.nav-columns {
  display: flex;
  width: 100%;
}

.nav-column {
  margin-right: 50px;
}

.nav-title {
  font-weight: bold;
  margin-bottom: 10px;
  font-size: 18px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  margin-bottom: 5px;
}

nav ul li a {
  color: #939494;
  text-decoration: none;
}
</style>