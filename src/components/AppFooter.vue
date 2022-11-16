<script>
export default {
  name: 'AppFooter',
}
</script>

<template>
  <footer>
    <div class="footer-t">
      <div class="link-f">

          <h4>DC COMICS</h4>
          <nav>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>
          </nav>

          <h4>SHOP</h4>
          <nav>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </nav>

      </div>

      <div class="link-f">
        <h4>DC</h4>
        <nav>
          <ul>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </nav>
      </div>

      <div class="link-f">
        <h4>SITES</h4>
        <nav>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </nav>
      </div>


    </div>

  </footer>
</template>


<style lang="scss" scoped>
  footer{
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;
    display: flex;
    height: 400px;
    align-items: center;
    .footer-t{
      background-image: url(../assets/img/dc-logo-bg.png);
      background-position: right;
      background-repeat: no-repeat;
      width: 70%;
      margin: 0 auto;
      padding: 35px;
      display: flex;
      .link-f{
        margin-right: 30px;
        h4{
          margin-bottom: 15px;
          color: white;
        };
        nav{
          ul{
            list-style: none;
            margin-bottom: 15px;
            li{
              padding: 4px 0px;
              a{
                text-decoration: none;
                color: #797979;
              }
            }
          }
        }
      }
    }
  }
</style>