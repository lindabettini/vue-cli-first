<template>
	<div>
		<Title />
		<Hero />
		<footer>Developed by Linda Class #52</footer>
	</div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";
export default {
	name: "App",
	components: {
		Title,
		Hero,
	},
};
</script>

<style lang="scss"></style>
