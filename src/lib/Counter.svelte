<script lang="ts">
  let count: number = 2;
  const increment = () => {
    count = count * count;
  }
</script>

<button on:click={increment}>
  count is {count}
</button>
