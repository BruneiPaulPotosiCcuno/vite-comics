<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
<footer>
  <div class="footer-container">
    <div class="footer-left">
      <a href="#" class="signup-btn">SIGN-UP NOW!</a>
    </div>
    <div class="footer-right">
      <ul class="social-links">
        <a>FOLLOW US</a>
        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
      </ul>
    </div>
  </div>
</footer>
</template>

<style scoped lang="scss">
footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

.footer-container {
  height: 70px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
}

.signup-btn {
  
  color: #fff;
  text-decoration: none;
  padding: 10px 20px;
  border-radius: 1px;
  border: 2px solid #0072bb;
}

.social-links {
  list-style: none;
  display: flex;
  padding: 0;
  margin: 0;
}

.social-links li {
  margin-left: 10px;
}

.social-links a {
  color: #0072bb;
  font-size: 20px;
  font-weight: 600;
}
</style>