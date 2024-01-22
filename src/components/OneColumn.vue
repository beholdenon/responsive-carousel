<script setup>
const props = defineProps(['img']);
</script>

<template>
<div class="carousel-slide image-map">
	<img :src="props.img" />
</div>
</template>
