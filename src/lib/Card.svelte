<script>
  import Icon from '@iconify/svelte';
  
  export let title = "Please specify a title";
  export let desc = "Please specify a description";
  export let icon = "bx:bx-home";
</script>

<div class="bg-yellow-600 shadow-lg hover:border hover:border-slate-200 transition border border-yellow-600 box-content rounded-lg p-3">
  <span class="flex flex-row items-center mb-2">
    <Icon icon={icon} class="text-2xl mr-1" />
    <h1 class="font-bold text-xl">{title}</h1>
  </span>
  <p>{desc}</p>
</div>
