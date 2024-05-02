<script>
  import { getContext } from "svelte";
  const test = getContext("test");
</script>

<h1>About</h1>
<p>
  <a href="/">Go home</a>
</p>

<pre>{test.test}</pre>
