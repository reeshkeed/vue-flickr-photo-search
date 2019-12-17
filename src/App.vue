<template>
  <div id="app">
    <nav class="bg-white border-b p-4">
      <div class="container mx-auto flex items-center justify-between flex-wrap">
        <div class="flex items-center flex-shrink-0 text-white mr-6">
          <img class="mr-1" alt="Vue logo" width="30" src="../static/img/vue.svg" />
          <img alt="Vue logo" width="75" src="../static/img/flickr.svg" />
          <span class="font-semibold text-xl tracking-tight"></span>
        </div>
        <div class="block lg:hidden">
          <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
            <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
          </button>
        </div>
        <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
          <div class="text-sm lg:flex-grow">
            <!-- <router-link to="/">Home</router-link>
            <router-link to="/about">About</router-link> -->
          </div>
          <div class="flex">
            <input class="bg-gray-200 focus:outline-none focus:border-gray-500  border border-gray-300 rounded py-2 px-4 block w-full appearance-none leading-normal" type="email" placeholder="Search">
            <a href="#" class="flex items-center inline-block text-sm px-4 py-2 ml-2 leading-none border rounded text-green-600 border-green-600 hover:border-transparent hover:text-white hover:bg-green-600 mt-4 lg:mt-0">Search</a>
          </div>
        </div>

      </div>
    </nav>

    <router-view />
  </div>
</template>

<style lang="sass">
  
</style>
