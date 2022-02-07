<template>
	<div>
		<Title />
		<main>
			<ul>
				<li>Link 1</li>
				<li>Link 2</li>
				<li>Link 3</li>
				<li>Link 4</li>
			</ul>
		</main>
		<footer>Developed by Linda Class #52</footer>
	</div>
</template>

<script>
import Title from "./components/Title.vue";
export default {
	name: "App",
	components: {
		Title,
	},
};
</script>

<style lang="scss"></style>
