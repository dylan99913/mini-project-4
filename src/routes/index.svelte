<script>
    import Color from '$lib/Color.svelte';
    let colorName = 'Pink';
    let color2 = 'Pink';
</script>

<div>
    <h1 class="text-primary">Play with Colors</h1>
</div>

<div>
    <input bind:value={colorName} />
    <Color color={colorName} />
</div>

<div>
    <input bind:value={color2} />
    <Color color={color2} />
</div>


<style>
    input {
   	 padding: 0.5em;
   	 text-align: center;
    }
    div {
   	 text-align: center;
   	 margin: 3em auto;
    }
</style>