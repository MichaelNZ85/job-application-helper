<script lang="ts">
    import {Alert, Button} from 'flowbite-svelte';
</script>

<Alert color="green">
    <span class="font-medium">Big purrs from the puddy!</span>
</Alert>
<Button color="purple">Purple</Button>
  
  <style lang="postcss">
    :global(html) {
      background-color: theme(colors.gray.400);
    }
  </style>