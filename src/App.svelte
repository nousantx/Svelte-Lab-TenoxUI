<script>
import TenoxUI, { Color } from './TenoxUI';
import {
    onMount
} from 'svelte';
// Apply TenoxUI
onMount(() => {
  Color();
  TenoxUI();
})
</script>

<main class="display-flex flex-parent-center bg-0d0d0d tc-white p-1rem">
  <h1 class="fs-1.5rem">Tenox<span class="tc-[primary]">UI</span></h1>

  <h1 class="fs-1.5rem mh-1rem">x</h1>
  <h1 class="fs-1.5rem tc-[svelte]">Svelte</h1>
</main>

<style>
  :root {
    --primary: #d2e603;
    --svelte: #FF3E00;
    font-family: inter, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }
  *,
  *::before,
  *::after
  
  {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

</style>
