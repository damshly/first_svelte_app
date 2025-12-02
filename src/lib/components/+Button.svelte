<script type="ts">
</script>

<button on:click>
    <slot>hi</slot>
</button>

<style>
    button {
        padding: 0.5em 1em;
        border: none;
        background-color: #6200ee;
        color: white;
        border-radius: 4px;
        cursor: pointer;
        font-size: 1em;
    }

    button:hover {
        background-color: #3700b3;
    }
</style>