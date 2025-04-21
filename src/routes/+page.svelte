<script>
import { sdk } from "@farcaster/frame-sdk";
import { onMount } from "svelte";

onMount(async () => {
    await sdk.actions.ready();
});
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
