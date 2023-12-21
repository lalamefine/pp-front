<script>
	import Content from "$lib/Content.svelte";
  import Head from "$lib/Head.svelte";
	import Nav from "$lib/Nav.svelte";
</script>

<div id="main">
  <Head />
  <Content>
    <slot></slot>
  </Content>
</div>

<style>
  #main {
    display: flex;
    flex-direction: column;
    height: 100vh;
    width: 100vw;
  }

  #d-flex {
    display: flex;
    width: 100vw;
    height: 100%;
  }
</style>