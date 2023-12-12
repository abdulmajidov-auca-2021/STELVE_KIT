<script>
  import Hero from "$lib/Hero.svelte";
  import Info from "$lib/Info.svelte";
  import Partners from "$lib/Partners.svelte";
  import Team from "$lib/Team.svelte";
</script>

<div>
  <Hero />
  <Partners />
  <Info />
  <Team />
</div>

<style>
    :global(*) {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Times New Roman', Times, serif;
  }
</style>
