<script lang="ts">
  let count: number = 2;
  let name: string = "";
  const increment = () => {
    count = count * count;
  };
</script>

<button on:click={increment}>
  count is {count}
</button>
<h1>My name is {name}</h1>
<input
  value={name}
  on:input={(event) => {
    name = event.currentTarget.value;
  }}
/>
