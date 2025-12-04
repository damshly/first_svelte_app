<script lang="ts">
    import type { Snippet } from "svelte";

    const { label }: { label: Snippet<[]> } = $props();
</script>

<div class="bg-color-red">
    {@render label()}
</div>
