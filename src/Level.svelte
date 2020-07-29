<script>
  export let obj;
  let description=obj.description || "Unknown";
  let highlighted = obj.highlighted || false;
  let todo = obj.todo || false;
</script>

<main>
  <span class="level" class:highlighted class:todo>{description}</span>
</main>

<style>
  .level {
    margin-block-end: 1px;
    opacity: 0.15;
    padding: 0.5rem;
    display: flex;
  }
  .level.highlighted {
    border: 2px solid #00ff00;
    opacity: 1;
  }
  .level.todo {
    background: #eee;
    opacity: 1;
  }
</style>
