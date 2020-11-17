<template>
  <div class="flex justify-around items-center">
    <img class="h-24 rounded-3xl" src="https://images.unsplash.com/photo-1584013286182-be9df31899bb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80 " alt="Ice Cream">
    <div class="flex flex-col">
      <span class="text-main font-bold text-lg">Blueberry Special</span>
      <span class="text-purple-500 text-xl">$12.00</span>
      <div class="flex items-center">
        <button class="px-2 bg-main bg-opacity-25 font-bold">-</button>
        <span class="mx-3 text-main font-bold">2</span>
        <button class="px-2 bg-main font-bold text-white">+</button>
      </div>
    </div>
    <div>
      <button>
        <svg class="text-red-800" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="3 6 5 6 21 6"></polyline><path d="M19 6v14a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V6m3 0V4a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"></path><line x1="10" y1="11" x2="10" y2="17"></line><line x1="14" y1="11" x2="14" y2="17"></line></svg>
      </button>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>