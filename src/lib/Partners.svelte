<script>
  import FacebookIcon from "/Group (1).svg";
  import AirbnbIcon from "/abc1.svg";
  import SpotifyIcon from "/spotify.svg";
  import MicroIcon from "/micro.svg";
  import GoogleIcon from "/google.svg";
</script>

<section>
  <div class="partners_header">
    <h5>partners</h5>
    <h3>Lorem Ipsum Dolor</h3>
    <p>
      Lorem ipsum, dolor sit amet consectetur <br />
      adipisicing elit.
    </p>
  </div>
  <div class="partners_images">
    <img src={GoogleIcon} alt="" />
    <img src={MicroIcon} alt="" />
    <img src={AirbnbIcon} alt="" />
    <img src={FacebookIcon} alt="" />
    <img src={SpotifyIcon} alt="" />
  </div>
  <div class="link_container">
    <a class="link" href="/services">Learn More</a>
  </div>
</section>

<style>
  .partners_header {
    margin-top: 20px;
    text-align: center;
  }

  .partners_header h5 {
    color: #74c69d;
    text-transform: uppercase;
    font-weight: bold;
    letter-spacing: 2px;
    font-size: 10px;
    font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
      "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  }

  .partners_header h3 {
    margin: 10px 0;
  }
  .partners_header p {
    font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
      "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  }
  .partners_images {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 70px;
    margin-top: 40px;
  }
  .link_container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
  }
  .link {
    display: inline-block;
    margin-top: 10px;
    background-color: #000;
    color: #fff;
    padding: 10px 28px;
    text-decoration: none;
    border-radius: 4px;
  }
</style>
