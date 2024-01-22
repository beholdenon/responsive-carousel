<script setup>
   import Image from './Image.vue';
   import Type from './Type.vue';
   const props = defineProps(['img1', 'img2', 'headline', 'body', 'link', 'eyebrow', 'collage', 'reverse']);
</script>

<template>
   <div class="carousel-slide col-3" :class="{'collage': props.collage, 'reverse': props.reverse}">
      <ul>
         <li class="img-col">
            <Image :src="props.img1" />
         </li>

         <li class="text-col">
            <Type :headline="props.headline" :body="props.body" :link="props.link" :eyebrow="props.eyebrow" />
         </li>

         <li class="img-col">
            <Image :src="props.img2" />
         </li>
      </ul>
   </div>
</template>

<style scoped>
   .col-3.collage .text-col {
      order: 3;
   }

   .col-3.reverse .text-col {
      order: -1;
   }

   .text-col {
      width: 42%;
   }
   .img-col {
      width: 29%;
   }
</style>
