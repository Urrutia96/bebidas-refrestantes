<template>
  <div class="fixed top-0 right-0 h-screen w-2/6 bg-white shadow-lg py-10">
    <div class="flex justify-center items-center">
      <!-- BoxIcon: basket -->
      <svg class="text-main fill-current w-8 h-8" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M21,9h-1.42l-3.712-6.496l-1.736,0.992L17.277,9H6.723l3.146-5.504L8.132,2.504L4.42,9H3C2.688,9,2.395,9.146,2.205,9.393 c-0.189,0.248-0.252,0.57-0.17,0.87l2.799,10.264C5.071,21.395,5.865,22,6.764,22h10.473c0.898,0,1.692-0.605,1.93-1.475 l2.799-10.263c0.082-0.3,0.02-0.622-0.17-0.87C21.605,9.146,21.312,9,21,9z M17.236,20C17.236,20,17.236,20,17.236,20v1V20H6.764 L4.31,11H19.69L17.236,20z"></path><path d="M9 13H11V18H9zM13 13H15V18H13z"></path></svg>
      <span class="ml-10 text-3xl font-bold text-main">My Order</span>
      <img class=" ml-10 h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80" alt="perfil photo">
    </div>
    <div class="h-full flex flex-col justify-between">
      <div class="flex flex-col justify-around">
        <div class="p-6 grid grid-cols-1 gap-6">
          <OrderProduct />
          <OrderProduct />
          <OrderProduct />
        </div>
      </div>
      <div class="border-t-2 border-gray-200 p-4">
        <div class="flex justify-between">
          <span class="text-xl text-gray-600">Delivery</span>
          <span class="text-xl text-main font-bold">Free</span>
        </div>
        <div class="flex justify-between">
          <span class="text-xl text-gray-600">Total</span>
          <span class="text-xl text-main font-bold">45.00 usd</span>
        </div>
        <button class="inline-block w-full py-3 rounded-lg bg-main text-white font-bold text-xl text-center uppercase">Checkout</button>
      </div> 
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>