<template>
	<div class="about-page">

		<h1 class="page-title">About</h1>

		<p class="about-me">Bitcoin only is an open source website created to showcase the highest quality Bitcoin resources.</p>

	</div>
</template>

<style lang="scss" scoped>
@import 'assets/css/pages.scss';

.about-me {
	max-width: 800px;
}
</style>

<script>
export default {

	name: 'AboutPage',

	head: {
		title: 'About - Bitcoin Only',
		meta: [
			{ hid: 'description', name: 'description', content: 'About Bitcoin Only' }
		]
	}

}
</script>
