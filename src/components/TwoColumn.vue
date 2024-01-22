<script setup>
	import Image from './Image.vue';
	import Type from './Type.vue';
	const props = defineProps(['img', 'headline', 'body', 'link', 'eyebrow', 'reverse']);
</script>

<template>
	<div class="carousel-slide col-2" :class="{'reverse': props.reverse}">
		<ul>
			<li class="img-col">
				<Image :src="props.img" />
			</li>

			<li class="text-col">
				<Type :headline="props.headline" :body="props.body" :link="props.link" :eyebrow="props.eyebrow" />
			</li>
		</ul>
	</div>
</template>

<style scoped>
.col-2.reverse .img-col {
	order: 2;
}

.text-col {
	width: 44%;
}

.img-col {
	width: 56%;
}
</style>