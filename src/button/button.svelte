<script lang="ts">
  export let type: "primary" | "secondary" = "primary";
</script>

<button class={type}>Hello button !</button>

<style lang="scss">
  button {
    cursor: pointer;
    border-radius: 0.25rem;
    padding: 0.5rem 1rem;
  }

  button.primary {
    background-color: var(--dark3);
    color: var(--light5);
    border: 1px solid var(--light2);
  }

  button.secondary {
    background-color: var(--dark1);
    border-color: var(--dark3);
  }
</style>
