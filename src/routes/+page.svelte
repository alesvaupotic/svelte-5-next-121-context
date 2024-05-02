<script>
  import { getContext } from "svelte";

  const test = getContext("test");
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>

<pre>{test.test}</pre>
