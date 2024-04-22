<script lang="ts">

  import { onMount } from 'svelte';

  onMount(() => {
    const link = document.createElement('link');
    link.rel = 'stylesheet';
    link.href = '/src/css/main.min.css';
    document.head.appendChild(link);
  });


</script>

<nav>
  <a href="/">Ingredients</a>
  <a href="/recipes">Recipes</a>
</nav>

<h1>Home</h1>
<p>This is the home page1.</p>


