<template>
  <div class="px-4 py-2 rounded-lg bg-opacity-50 w-full max-w-xs" :class="color">
    <div class="flex justify-between items-center">
      <span class="font-bold">Blueberry <br /> Special</span>
      <div class="px-1 py-2 rounded-full" :class="color">
        <span class="font-bold text-lg">20%</span>
      </div>
    </div>
    <div class="flex justify-between items-center mt-2">
      <div class="font-hairline text-sm flex flex-col">
        <span class="">Calories: 20 kcal</span>
        <span class="">Size: 10 oz</span>
      </div>
      <span class="text-lg font-bold">$12</span>
    </div>
  </div>
</template>

<script>
export default {
  props: [
    'color'
  ]
}
</script>

<style>

</style>