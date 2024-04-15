<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div
    class="flex flex-col items-center justify-center min-h-screen bg-zinc-100 p-4 text-zinc-800 dark:text-white"
  >
    <div class="max-w-2xl mx-auto text-center">
      <img
        class="w-32 h-32 rounded-full mx-auto mb-4"
        src="https://placehold.co/128x128"
        alt="Profile image"
      />
      <h1 class="text-4xl font-bold mb-2">CREATIVE PORTFOLIO</h1>
      <p class="mb-4">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis a metus ac
        nulla consequat aliquet id quis turpis. Etiam nec elit tristique,
        fermentum nunc vel, gravida nunc. Cras aliquet, nunc sit amet
        scelerisque ullamcorper, leo dolor tempus magna, vitae cursus nisl dui
        at ipsum. Donec et sapien pellentesque, fermentum felis vitae, ultricies
        eros.
      </p>
      <div class="mb-8 px-6">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div class="bg-white bg-orange-200 p-4 rounded-lg shadow-md">
            <h3 class="text-lg font-bold mb-2">Hobbies</h3>
            <p class="text-zinc-600">
              I love watching youtube videos and listening to music. During my
              free time, I like to scroll through social media and playing
              mboile games with my friends.
            </p>
          </div>
          <div class="bg-white bg-orange-200 p-4 rounded-lg shadow-md">
            <h3 class="text-lg font-bold mb-2">Interest</h3>
            <p class="text-zinc-600">Cooking</p>
            <p class="text-zinc-600">Photography</p>
            <p class="text-zinc-600">Watching k-drama</p>
            <p class="text-zinc-600">Shopping</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style></style>
