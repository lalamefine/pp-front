
<div class="content">
  <div class="padder">
    <slot></slot>
  </div>
</div>

<style>
  .content {
    display: flex;
    background-color:rgba(255, 255, 255, 0.02);
    flex-direction: column;
  }
  .padder {
    padding: 0px 20px 10px 20px;
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