<script>
  export let initialCounter = 0;
  let contador = initialCounter;

  function handleclick() {
    contador++;
  }
</script>

<main>
  <button on:click={handleclick}>Incrementar</button>
  <span>{contador}</span>
</main>

<style>
  span {
    color: red;
  }
</style>
