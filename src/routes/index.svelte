<script>
  import {onMount} from "svelte";
  import {getEvents} from "$lib/data.js";

  let events
  onMount(async () => {
    events = await getEvents()
  })
</script>
<style>
    * {
        font-family: monospace;
        font-size: 12px;
    }
</style>
<strong>Welcome to The Moon</strong>
<p><a href="https://kit.svelte.dev/docs/introduction" target="_blank">kit.svelte.dev</a> Doc here</p>
