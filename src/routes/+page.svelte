<script lang="ts">
    import Button from "../lib/components/+Button.svelte";
</script>

{#snippet label()}
    <h1 on:click={() => alert('clicked')}>Hello</h1>
{/snippet}

<div>
    <Button {label} />
</div>
