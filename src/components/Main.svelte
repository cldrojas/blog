<script>
  import Sidebar from "./Sidebar.svelte";
</script>

<main class="Main">
  <div class="Main-container">
    <div class="Main-content">
      <slot />
      <Sidebar />
    </div>
  </div>
</main>

<style>
  .Main-container {
    /*  min-height: calc(100vh - 203px); */
    display: grid;
    grid-template-columns: minmax(auto, 1024px);
    justify-content: center;
    align-items: center;
  }
  .Main-content {
    margin: 2em 0 0 0;
    display: grid;
    grid-template-columns: 3fr 1fr;
    gap: 60px;
    justify-content: space-between;
  }
</style>
