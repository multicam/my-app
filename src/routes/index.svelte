<script>
  import {onMount} from "svelte";
  import {getEvents} from "$lib/data.js";

  let events
  onMount(async () => {
    events = await getEvents()
  })
</script>
<h1>Welcome to The Moon</h1>
<p><a href="https://kit.svelte.dev/docs/introduction" target="_blank">kit.svelte.dev</a> Doc here</p>
