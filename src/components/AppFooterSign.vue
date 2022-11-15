<script>
export default {
  name: 'AppFooterSign'
}
</script>

<template>
  <footer>
    <div class="footer-b">

      <button>
        SIGN-UP NOW!
      </button>

      <div class="link-b">
        <h3>FOLLOW US</h3>
          <nav>
            <ul>
              <li><a href=""><img src="../assets/img/footer-facebook.png" alt=""></a></li>
              <li><a href=""><img src="../assets/img/footer-twitter.png" alt=""></a></li>
              <li><a href=""><img src="../assets/img/footer-youtube.png" alt=""></a></li>
              <li><a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
              <li><a href=""><img src="../assets/img/footer-periscope.png" alt=""></a></li>
            </ul>
          </nav>
      </div>

    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer{
  width: 100%;
  background-color: #303030;
  button{
    padding: 10px;
    border: 2px solid #0282f9;
    color: white;
    background-color: #303030;
  }
  .footer-b{
      width: 70%;
      margin: 0 auto;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      .link-b{
        display: flex;
        align-items: center;
        h3{
          padding: 10px;
          color: #0282f9;
        }
        nav{
          ul{
            display: flex;
            list-style: none;
            li{
              padding: 0 5px;
            }
          }
        }
      }
    }
}
</style>