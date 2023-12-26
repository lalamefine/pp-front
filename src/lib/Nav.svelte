
<nav>
    <a href="/"><div class="card">Home</div></a>
    <a href="/cv"><div class="card">CV</div></a>
    <a href="/projets"><div class="card">Projets</div></a>
</nav>

<style>
  nav {
    width: 100vw;
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
  div.card:hover {
    border-bottom: 4px solid rgb(255, 255, 255);
    padding-bottom: 3px;
    /* background-color: rgb(135, 214, 238); */
    color: white;
    cursor: pointer;
  }
  a{
    text-align: center;
    ;
    width: 100%;
    font-size: larger;
  }
</style>