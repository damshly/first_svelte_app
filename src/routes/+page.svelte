<script>
    let count = $state(0)

    $effect(() => {
        console.log(count);
        
    })
    let dubled = $derived(count * 2)
    let dubled2 = count * 2
</script>

<button onclick={() => {count++
    dubled2 = count * 2
}}>click</button>
<h1>{dubled}</h1>
<h1>{dubled2}</h1>
<h1>{count}</h1>
<button onclick={() => {
    count = 0
}} >reset</button>