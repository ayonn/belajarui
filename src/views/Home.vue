<template>
<div style="height:1000px" class="bg-gray-400 box-border w-7/12 p-7 rounded-xl">
  <div>
    <h1 class="text-2x1 h-12">sign in</h1>
  </div>
  <div>
    <input class="placeholder-gray-500 opacity-100 bg-gray-300 mt-2 w-full h-10 rounded pl-3 pb-1" style=" ml-4 mt-2" placeholder="email" <!-- form line -- />
  </div>
  <div>
    <input class="placeholder-gray-500 opacity-100 bg-gray-300 mt-4 w-full h-10 rounded pl-3 pb-1" placeholder="password" />
  </div>
  <div class="flex justify-center">
    <input class="placeholder-gray-500 opacity-100 bg-gray-300 mt-2 w-10/12 h-7 rounded-md pl-3 pb-1 text-xs" placeholder="... confirm password..." />
  </div>
  <div class="divide-y-2 divide-solid divide-rose-400">
    <div>
      <button class="bg-red-400 rounded ml-10 mt-4 mb-2 w-9/12 h-10 text-gray-100 pb-1">go!</button>
    </div>
    <div>
      <button class="text-white bg-blue-700 rounded-3xl ml-10 my-2 w-48 h-9 mr-8">google</button>
    </div>
  </div>
</div>

</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld
  },
};
</script>
