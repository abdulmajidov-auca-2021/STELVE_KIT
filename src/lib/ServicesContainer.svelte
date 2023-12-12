<script>
  import Vector from "/Vector.svg";

  let cards = [
    {
      id: 1,
      status: "Basic",
      price: "100",
    },
    {
      id: 2,
      status: "Plus",
      price: "250",
    },
    {
      id: 3,
      status: "Pro",
      price: "400",
    },
  ];
</script>

<section class="cards-container">
  {#each cards as card}
    <div class="card">
      <p>{card.status}</p>
      <span class="bold">${card.price}</span>
      <span class="gray">/month</span>
      <p class="gray">
        Lorem ipsum, dolor sit amet <br /> consectetur adipisicing elit.
        Suscipit <br /> nemo hic quos, ab, dolor aperiam
      </p>
      <div class="vector-container">
        <img src={Vector} alt="" />
        <p>Lorem ipsum, dolor sit</p>
      </div>
      <div class="vector-container">
        <img src={Vector} alt="" />
        <p>Lorem ipsum, dolor sit</p>
      </div>
      <div class="vector-container">
        <img src={Vector} alt="" />
        <p>Lorem ipsum, dolor sit</p>
      </div>
      <div class="vector-container">
        <img src={Vector} alt="" />
        <p>Lorem ipsum, dolor sit</p>
      </div>
    </div>
  {/each}
</section>

<style>
  .cards-container {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    margin-top: 60px;
    padding-bottom: 50px;
  }

  .card {
    border-radius: 5px;
    background: #fff;
    box-shadow: 3px 4px 12px 1px rgba(0, 0, 0, 0.25);
    padding: 30px 20px;
    text-align: center;
  }

  .bold {
    font-size: 2.5rem;
    font-weight: bold;
  }

  .gray {
    color: #21252980;
    margin-bottom: 20px;
  }

  .vector-container {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 20px;
  }
</style>
