<template>
	<div id="jumbotron">
		<h2>HELLO WORLD !</h2>
		<div id="confetti">&#127881; &#127881; &#127881;</div>
	</div>
</template>

<script>
export default {
	name: "Hero",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#jumbotron {
	height: 300px;
	text-align: center;
	background-color: lightskyblue;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	flex-wrap: nowrap;
}

#confetti {
	font-size: 35px;
}
</style>
