
<nav>
    <a href="/"><div class="card">Home</div></a>
    <a href="/cv"><div class="card">CV</div></a>
    <a href="/projects"><div class="card">Projets</div></a>
</nav>

<style>
  nav {
    height: 100%;
    width: 100vw;
    display: flex;
    align-items: center;
    justify-content: space-around;
  }
  div.card {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    border: 1px solid #fff1;
    border-radius: 5px;
    min-width: 100px;
    min-height: 50px;
    padding: 5px;
  }
  div.card:hover {
    background-color: rgb(135, 214, 238);
    color: white;
    cursor: pointer;
  }
  a{
    padding: 8px; 
    font-size: larger;
  }
</style>