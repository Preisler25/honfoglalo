<script lang="ts">
  import Card from '$lib/Card.svelte';
</script>

<svelte:head>
  <title>Honfoglaló</title>
</svelte:head>

<main class="bg-gray-800 min-h-screen text-white">
  <!-- sziasztok -->
  <h1 id="title" class="font-black text-center text-6xl p-4 shadow-lg">Honfoglaló</h1>
  <div class="h-full  grid grid-rows-4 grid-cols-1 md:grid-cols-2 md:grid-rows-2 gap-3 mx-3">
    <Card title="Mi az a honfoglaló?" desc="loremlorem preisler lorem lorem ipsum preisler lorem ipsum gaming" />
    <Card title="Mikor?" desc="Oktober 27. 19:30" />
    <Card title="Események" desc="lesz sok fun event sok fun ember altal szervezve gyere eventre :3" />
    <Card title="Hol jelentkezek?" desc="It itt itt ebbena  boxban nyomj ra hogy jelentkezz oke? ok" />
  </div>
  
</main>