<script setup>
	const props = defineProps(['src']);
</script>

<template>
	<img :src="props.src" alt="Alt Text" />
</template>

<style scoped>
	img {
	  width: 100%;
	  height: auto;
	  object-fit: contain;
	}
</style>