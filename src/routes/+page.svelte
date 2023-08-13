<script>
    let a = 15;
    function add() {
        a = a+1;
    }
</script>

<h1>Hello a is {a}</h1>
<button on:click={add}>Click</button>