<script setup>
	import Image from './Image.vue';
	const props = defineProps(['img']);
</script>

<template>
	<div class="carousel-slide">
		<Image :src="props.img" />
	</div>
</template>