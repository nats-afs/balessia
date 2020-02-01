<template>
  <div class="container mx-auto my-4 p-3">
    <div
      v-for="i in 6"
      :key="i"
      class="inline-block max-w-sm rounded overflow-hidden shadow-xl mx-3 my-6"
    >
      <img class="w-full" :src="`/img/gallery-${i}.jpg`" alt="Sunset in the mountains" />
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2 border-gray-900">The Coldest Sunset</div>
        <!-- <p class="text-gray-700 text-base">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis
          eaque, exercitationem praesentium nihil.
        </p> -->
      </div>
      <div class="px-6 py-4">
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2"
        >#photography</span>
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2"
        >#travel</span>
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700"
        >#winter</span>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data: () => ({
    
  })
};
</script>