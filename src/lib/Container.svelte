
<div class="content">
  <slot></slot>
</div>

<style>
  .content {
    margin: 20px 0px 0px 0px;
    display: flex;
    flex-direction: column;
  }
  @media (max-width: 1000px) {
    .content {
      width: 100vw;
    }
  }
  @media (min-width: 1000px) {
    .content {
      width: 1000px;
    }
  }
  @media (min-width: 1400px) {
    .content {
      width: 1200px;
    }
  }
</style>