<script>
  import { Spinner, Button } from "flowbite-svelte";
</script>

<div class="flex justify-center items-center flex-col gap-y-2">
  <Button color="purple">
    <Spinner class="me-3" size="4" color="blue" />
    <p class="opacity-75">Subiendo archivo y extrayendo el texto...</p>
  </Button>
</div>
