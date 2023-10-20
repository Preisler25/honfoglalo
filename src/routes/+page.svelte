<script lang="ts">
  import Card from '$lib/Card.svelte';
</script>

<svelte:head>
  <title>Honfoglaló</title>
</svelte:head>

<main class="bg-gray-800 min-h-screen text-white">
  <h1 id="title" class="font-black text-center text-6xl p-4 shadow-lg">Honfoglaló</h1>
  <div class="h-full  grid grid-rows-4 grid-cols-1 md:grid-cols-2 md:grid-rows-2 gap-3 mx-3">
    <Card />
    <Card />
    <Card />
    <Card />
  </div>
  
</main>