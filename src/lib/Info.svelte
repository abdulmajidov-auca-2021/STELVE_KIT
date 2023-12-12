<script>
  import Icon1 from "/image1.svg";
  import Icon2 from "/image2.svg";
</script>

<section>
  <div class="info-container">
    <div>
      <img src={Icon1} alt="" />
    </div>
    <div class="info-text">
      <h3>Lorem ipsum dolor sit <br /> amet consectetur</h3>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br />
        Suscipit nemo hic quos, ab, dolor aperiam nobis cum est eos <br /> error
        ipsum, voluptate culpa nesciunt delectus iste?
      </p>
      <a class="link" href="/services">Learn More</a>
    </div>
  </div>
  <div class="info-container">
    <div class="info-text">
      <h3>Lorem ipsum dolor sit <br /> amet consectetur</h3>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. <br />
        Suscipit nemo hic quos, ab, dolor aperiam nobis cum est eos <br /> error
        ipsum, voluptate culpa nesciunt delectus iste?
      </p>
      <a class="link" href="/services">Learn More</a>
    </div>
    <div>
      <img src={Icon2} alt="" />
    </div>
  </div>
</section>

<style>
  .info-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 100px 60px 20px 60px;
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

  .info-text p {
    margin: 10px 0;
  }
</style>
