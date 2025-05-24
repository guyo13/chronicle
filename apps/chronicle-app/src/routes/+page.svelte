<script lang="ts">
  import { invoke } from "@tauri-apps/api/core";

  let selectedDate = $state<Date | undefined>(undefined);
  let name = $state("");
  let greetMsg = $state("");
</script>

<style>
</style>
