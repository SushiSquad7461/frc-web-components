<script lang="ts">
  import { setNt4Context, getNt4Context } from "@frc-web-components/svelte";
  import ThemeChooser from "./components/ThemeChooser.svelte";
  import Dashboard from "./components/Dashboard.svelte";
  import { getEntry } from "@frc-web-components/svelte";

  // Set robot IP address here
  setNt4Context('7461');

</script>

<div class="App">
  <ThemeChooser />
  <Dashboard />
</div>
