<script>
  let team = [
    {
      id: 1,
      name: "Peg Legge",
      job: "CEO",
      image: "/person1.svg",
    },
    {
      id: 2,
      name: "Peg Legge",
      job: "CEO",
      image: "/person2.svg",
    },
    {
      id: 3,
      name: "Peg Legge",
      job: "CEO",
      image: "/person3.svg",
    },
    {
      id: 4,
      name: "Peg Legge",
      job: "CEO",
      image: "/person4.svg",
    },
  ];
</script>

<section class="teams">
  <div class="teams_header">
    <h6>TEAM</h6>
    <h2>Our Talents</h2>
    <p>
      Lorem ipsum, dolor sit amet consectetur <br />
      Suscipit nemo hic quos, ab,
    </p>
  </div>
  <div class="members-container">
    {#each team as member}
      <div class="member-card">
        <img src={member.image} alt="" />
        <h3>{member.name}</h3>
        <p>{member.job}</p>
      </div>
    {/each}
  </div>
</section>

<style>
  .teams {
    padding: 20px 60px;
  }

  .teams_header {
    text-align: center;
    margin-top: 50px;
  }

  .teams_header h6 {
    color: #74c69d;
    font-size: 10px;
    font-weight: bold;
    letter-spacing: 2px;
    font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
      "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  }

  .teams_header h2 {
    margin: 10px 0;
  }

  .members-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 40px 0;
  }

  .member-card {
    border-radius: 5px;
    background: #fff;
    box-shadow: 3px 4px 12px 1px rgba(0, 0, 0, 0.25);
    padding: 15px 27px;
  }

  .member-card h3 {
    margin: 10px 0;
  }
</style>
