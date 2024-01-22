<script setup>
import OneColumn from './components/OneColumn.vue';
import TwoColumn from './components/TwoColumn.vue';
import ThreeColumn from './components/ThreeColumn.vue';
</script>

<template>
  <div class="page-container">
   <div class="carousel-container">
    <OneColumn img="https://images.bloomingdalesassets.com/is/image/BcomMedia/media/0111_0115_D_02_CAR_a_GIFTS_v1_VDAY.jpg?scl=1&fmt=webp&wid=1440" />
    <TwoColumn eyebrow="Eyebrow Here" img="https://images.ctfassets.net/m3h9iuk14rnq/WHDvVISDDYBXYnRmVhjsm/0a30ba27a05d2657aa85bd13dd1cd9ec/900x600.jpg" headline="Headline Here" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu quam non purus aliquet convallis. Etiam sit amet blandit felis. Proin sed tempor erat. Nulla facilisi." />
    <TwoColumn eyebrow="Eyebrow Here" img="https://images.ctfassets.net/m3h9iuk14rnq/WHDvVISDDYBXYnRmVhjsm/0a30ba27a05d2657aa85bd13dd1cd9ec/900x600.jpg" headline="Headline Here" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu quam non purus aliquet convallis. Etiam sit amet blandit felis. Proin sed tempor erat. Nulla facilisi." reverse=true />
    <ThreeColumn eyebrow="Eyebrow Here" link="Shop Now" img1="https://images.ctfassets.net/m3h9iuk14rnq/5HNDOhkCanLrTYNcts4foU/c99f9ac961f98accbf6dc528cf7d2e57/400x6001.jpg" img2="https://images.ctfassets.net/m3h9iuk14rnq/782khjo25Ef8haXJURJZOa/78739f2bd2252004c20be27414e9c958/400x6002.jpg" headline="Headline Here" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu quam non purus aliquet convallis. Etiam sit amet blandit felis. Proin sed tempor erat. Nulla facilisi." />
    <ThreeColumn link="Shop Now" img1="https://images.ctfassets.net/m3h9iuk14rnq/5HNDOhkCanLrTYNcts4foU/c99f9ac961f98accbf6dc528cf7d2e57/400x6001.jpg" img2="https://images.ctfassets.net/m3h9iuk14rnq/782khjo25Ef8haXJURJZOa/78739f2bd2252004c20be27414e9c958/400x6002.jpg" headline="Headline Here" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu quam non purus aliquet convallis. Etiam sit amet blandit felis. Proin sed tempor erat. Nulla facilisi." collage=true />
    <ThreeColumn link="Shop Now" img1="https://images.ctfassets.net/m3h9iuk14rnq/5HNDOhkCanLrTYNcts4foU/c99f9ac961f98accbf6dc528cf7d2e57/400x6001.jpg" img2="https://images.ctfassets.net/m3h9iuk14rnq/782khjo25Ef8haXJURJZOa/78739f2bd2252004c20be27414e9c958/400x6002.jpg" headline="Headline Here" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu quam non purus aliquet convallis. Etiam sit amet blandit felis. Proin sed tempor erat. Nulla facilisi." reverse=true />
   </div>
  </div>
</template>
