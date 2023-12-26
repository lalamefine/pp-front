<script>
	import Content from "$lib/Content.svelte";
	import Nav from "$lib/Nav.svelte";
</script>

<div id="website">
  <Nav />
  <Content>
    <slot></slot>
  </Content>
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