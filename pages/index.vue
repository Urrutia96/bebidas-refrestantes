<template>
  <div>
    <div class="w-full bg-cover bg-center" style="height:48rem; background-image: url(/img/background-cut2.jpg);">
      <Navbar />
      <div class="flex justify-end mt-8 mr-10">
        <div class="flex flex-col items-center">
          <img class="h-5 w-5" src="/img/svg/fb.svg" alt="Facebook">
          <img class="h-5 w-5 mt-5" src="/img/svg/tw.svg" alt="Facebook">
          <img class="h-5 w-5 mt-5" src="/img/svg/insta.svg" alt="Facebook">
        </div>
      </div>
      <div class="flex justify-between items-center container mx-auto">
        <div class="w-2/7">
          <span class="text-7xl xl:text-9xl text-main font-bold">Enjoy!</span>
          <p class="mt-1 text-white text-justify">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Molestiae soluta exercim voluptatum necessitatibus? dolorum volupta.</p>
          <form class="mt-5 flex items-center w-full">
            <input class="appearance-none focus:outline-none py-2 px-4 rounded-full w-full text-main placeholder-main placeholder-opacity-75" type="text" placeholder="Search your drink ">
            <button class="ml-2 p-2 bg-main rounded-full">
              <img class="h-5 w-5" src="/img/svg/search.svg" alt="search icon">
            </button>
          </form>
        </div>
        <div class="flex flex-col items-center -mr-10 xl:-mr-20">
          <div class="w-2 h-2 bg-white rounded-full"></div>
          <div class="w-2 h-2 bg-gray-300 rounded-full mt-3"></div>
          <div class="w-2 h-2 bg-gray-300 rounded-full mt-3"></div>
          <div class="w-2 h-2 bg-gray-300 rounded-full mt-3"></div>
        </div>
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
