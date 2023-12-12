<script>
  import Logo from "./Logo.svelte";
  import Navbar from "./Navbar.svelte";
</script>

<header class="header">
  <Logo />
  <Navbar />
</header>

<style>
  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 60px;
    background-color: #74C69D;
  }
</style>
