
<script>
  import { page } from '$app/stores';  
  import Home from "svelte-material-icons/Home.svelte";
  let path = '/';
  $: path = $page.route.id??'';
</script>

<div class="navbar">
  <div class=navborder></div>
  <nav>
      <a href="/cv"><div class="card" class:active={path=='/cv'}>CV</div></a>
      <a href="/"><div class="card" class:active={path=='/'}><Home /></div></a>
      <a href="/projets"><div class="card" class:active={path=='/projets'}>Projets</div></a>
  </nav>
  <div class=navborder></div>
</div>

<style>
  nav {
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
  div.card {
    border-bottom: 2px solid #fff1;
    padding: 5px;
    height: 100%;
    transition-duration: 200ms;
  }
  div.card:hover, div.card.active {
    border-bottom: 4px solid;
    padding-bottom: 3px;
    color: white;
    cursor: pointer;
  }
  div.card:hover {
    border-bottom: 4px solid rgb(255, 255, 255);
  }
  a{
    text-align: center;
    width: 100%;
    font-size: larger;
  }
  div.navbar {
    display: flex;
    width: 100vw;
  }
  div.navborder {
    height: 41px;
    flex-grow: 1;
    border-bottom: 2px solid #fff1;
  }
  @media (max-width: 1000px) {
    nav {
      width: 100vw;
    }
  }
  @media (min-width: 1000px) {
    nav {
      width: 1000px;
    }
  }
  @media (min-width: 1400px) {
    nav {
      width: 1200px;
    }
  }
</style>