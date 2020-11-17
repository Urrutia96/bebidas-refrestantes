<template>
  <div class="bg-purple-200 bg-opacity-50">
    <!-- Banner -->
    <div class="w-full bg-cover bg-center" style="height:48rem; background-image: url(/img/background-cut2.jpg);">
      <!-- Navigation Bar -->
      <Navbar />
      <!-- End Navigation Bar -->

      <!-- Social Links -->
      <div class="flex justify-end mt-8 container mx-auto">
        <div class="flex flex-col items-center">
          <a href="#">  
            <img class="h-5 w-5" src="/img/svg/fb.svg" alt="Facebook">
          </a>
          <a href="#">
            <img class="h-5 w-5 mt-5" src="/img/svg/tw.svg" alt="Facebook">
          </a>
          <a href="#">
            <img class="h-5 w-5 mt-5" src="/img/svg/insta.svg" alt="Facebook">
          </a>
        </div>
      </div>
      <!-- End Social Links -->

      <!-- Banner text -->
      <div class="flex justify-between items-center container mx-auto">
        <div class="w-2/7">
          <span class="text-7xl xl:text-9xl text-main font-bold">Enjoy!</span>
          <p class="mt-1 text-white text-justify">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Molestiae soluta exercim voluptatum necessitatibus? dolorum volupta.</p>
          <form class="mt-5 flex items-center w-full">
            <input class="appearance-none focus:outline-none py-2 px-4 rounded-full w-full text-main placeholder-main placeholder-opacity-75" type="text" placeholder="Search your drink ">
            <button class="ml-2 p-2 bg-main rounded-full hover:bg-opacity-50">
              <img class="h-5 w-5" src="/img/svg/search.svg" alt="search icon">
            </button>
          </form>
        </div>
        <div class="flex flex-col items-center">
          <div class="cursor-pointer w-2 h-2 hover:bg-white bg-white rounded-full"></div>
          <div class="cursor-pointer w-2 h-2 hover:bg-white bg-gray-300 rounded-full mt-3"></div>
          <div class="cursor-pointer w-2 h-2 hover:bg-white bg-gray-300 rounded-full mt-3"></div>
          <div class="cursor-pointer w-2 h-2 hover:bg-white bg-gray-300 rounded-full mt-3"></div>
        </div>
      </div>
      <!-- End Banner Text -->

      <!-- Cards -->
      <div class="flex justify-end items-center mt-20 container mx-auto text-white">
        <CardBanner color="bg-main-green" />
        <CardBanner color="bg-main-yellow" class="ml-10" />
        <CardBanner color="bg-main-purple" class="ml-10" />
      </div>
      <!-- End Cards -->
    </div>
    <!-- End Banner -->

    <!--Filter -->
    <div class="mt-24 container mx-auto flex justify-between">
      <div class="text-xl font-bold text-main">
        <a class="px-5 py-1 hover:bg-main hover:text-white" href="">All</a>
        <a class="px-5 py-1 bg-main text-white" href="">Popular Drinks</a>
        <a class="px-5 py-1 hover:bg-main hover:text-white" href="">Natural Smoothie</a>
        <a class="px-5 py-1 hover:bg-main hover:text-white" href="">Juices</a>
        <a class="px-5 py-1 hover:bg-main hover:text-white" href="">Yogurt</a>
      </div>
      <div>
        <button class="px-2 py-1 rounded-full bg-main-purple bg-opacity-50 hover:bg-opacity-25 flex items-center ">
          <img class="h-4 w-5" src="/img/svg/filter.svg" alt="filter icon">
          <span class="ml-2 text-lg">Filter</span>
        </button>
      </div>
    </div>
    <!-- End Filter -->

    <!-- Product Section -->
    <div class="mt-16 px-2 md:container md:mx-auto">
      <h2 class="text-main text-4xl font-bold">Popular Drinks</h2>
      <!-- Products -->
      <div class="mt-10 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8">
        <ProductCard />
        <ProductCard />
        <ProductCard />
        <ProductCard />
        <ProductCard />
        <ProductCard />
        <ProductCard />
        <ProductCard />
      </div>
      <!-- End Products -->
    </div>
    <!-- End Product Section -->

    <div class="mt-20">&nbsp;</div>

    <SideBar />
  </div>
</template>

<script>
export default {
  

}
</script>

<style>

</style>
