<script>
  import HeroImage from "/Group.svg";
</script>

<section class="hero">
  <div>
    <h4>WELCOME</h4>
    <h2 class="main-title">Lorem ipsum dolor sit <br /> amet consectetur</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing <br /> elit. Suscipit
      nemo hic quos, ab, dolor aperiam nobis <br /> cum est eos error ipsum,
      voluptate culpa nesciunt <br /> delectus iste?
    </p>
    <a class="explore_link" href="/services">Explore</a>
  </div>
  <div>
    <img src={HeroImage} alt="">
  </div>
</section>

<style>
  .hero {
    padding: 20px 60px;
    background-color: #74c69d;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .main-title {
    margin: 15px 0px;
  }

  .explore_link {
    display: inline-block;
    margin-top: 10px;
    background-color: #fff;
    color: black;
    padding: 10px 28px;
    text-decoration: none;
    border-radius: 4px;
  }

  .hero div img {
    width: 500px;
  }
</style>
