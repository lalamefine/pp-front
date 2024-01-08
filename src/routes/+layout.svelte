<script>
	import Container from "$lib/Container.svelte";
	import Nav from "$lib/Nav.svelte";
</script>

<div id="website">
  <Nav />
  <Container>
    <slot></slot>
  </Container>
</div>

<style>
  #website {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100vh;
    width: 100vw;
  }
</style>