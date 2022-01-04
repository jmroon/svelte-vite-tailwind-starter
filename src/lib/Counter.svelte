<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button class="bg-red-200 w-96 h-24 rounded-full" on:click={increment}>
  Clicks: {count}
</button>

<style>
 
</style>
