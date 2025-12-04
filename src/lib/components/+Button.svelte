<script lang="ts">
    import type {Snippet} from "svelte";

    const {header} = $props<{
        header: Snippet<[]>
    }>();
</script>

<div>
    {#if header}
        {@render header()}
    {/if}
</div>