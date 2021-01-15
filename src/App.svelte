<script>
    let count = 0;

    function sum() {
        count++;
    }
</script>

<p>Counter: {count}</p>
<button on:click={sum}> + </button>

<style>
</style>
