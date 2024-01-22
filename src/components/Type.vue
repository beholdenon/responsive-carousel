<script setup>
	const props = defineProps(['headline', 'body', 'link', 'eyebrow']);
</script>

<template>
	<div class="text-inner">
		<h4 v-if="props.eyebrow">{{props.eyebrow}}</h4>
		<h2 v-if="props.headline">{{props.headline}}</h2>
		<p v-if="props.body">{{props.body}}</p>
		<a v-if="props.link" href="#">{{props.link}}</a>
	</div>
</template>

<style scoped>
	.text-inner {
		width: 80%;
		text-align: center;
		max-width: 400px;
	}

	h1, h2, h3, h4, p, a {
		font-family: 'Avenir';
		color: #000;
	}

	h2 {
		text-transform: uppercase;
		font-size: 30px;
		line-height: 1em;
		margin: 0;
	}

	h4 {
		text-transform: uppercase;
		font-size: 15px;
		font-weight: 800;
		letter-spacing: 1px;
		margin: 0 auto 10px auto;
	}

	p {
		font-size: 14px;
	}

	a {
		text-transform: uppercase;
		font-size: 16px;
		font-weight: 800;
		text-decoration: underline;
	}

	@media screen and (min-width: 900px) {
		h2 {
			font-size: 40px;
		}
	}
</style>