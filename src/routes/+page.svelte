<script lang="ts">
  import { onMount } from "svelte";

  onMount(() => {
    const h1 = document.getElementById("demo");
    if (h1) {
      const span = document.createElement('span');
      span.innerText = "dynamic content";
      h1.append(span);
	}
  });
</script>

<h1>Welcome to SvelteKit</h1>
<p id="demo">Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
