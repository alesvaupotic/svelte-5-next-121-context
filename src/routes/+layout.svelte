<script>
  import { setContext } from "svelte";

	const { children } = $props();

	setContext('test',{test:"test"})
</script>

<a href="/">Home</a>
<a href="/about">About</a>

<main>
	{@render children()}
</main>

	

