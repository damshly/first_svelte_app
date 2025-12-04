<!-- <script lang="ts">
  import Button from "./+Button.svelte";

  const items = ["Home", "Profile", "Settings", "Logout"];
</script>

<nav class="flex gap-2">
  {#each items as item}
    <Button label={item} />
  {/each}
</nav> -->


<script lang="ts">
  const items = ["Home", "Profile", "Settings", "Logout"];
</script>

{#snippet Btn(label:string)}
  <button class="px-3 py-1 rounded bg-blue-500 text-white">{label}</button>
{/snippet}

<nav class="flex gap-2">
  {#each items as item}
    {@render Btn(item)}
  {/each}
</nav>
