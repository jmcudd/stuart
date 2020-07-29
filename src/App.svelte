<script>
  import Level from "./Level.svelte";
</script>

<div>
  <Level obj="{{ description: 'Level A' }}" />
  <Level obj="{{ description: 'Level B', highlighted: true }}" />
  <Level obj="{{ description: 'Level C', todo: true }}" />
  <Level obj="{{ description: 'Level D', todo: true }}" />
</div>
