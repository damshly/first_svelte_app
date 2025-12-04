<script lang="ts">
    import Header from "$lib/components/+Button.svelte";
</script>
<div>
    <Header>
        {#snippet header()}
            <h1>Hello</h1>
            <button class="bg-red-500">Click</button>      
        {/snippet}
    </Header>
</div>