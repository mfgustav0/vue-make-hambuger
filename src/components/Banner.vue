<template>
	<div id="main-barner">
		<h1>Make Your Burger</h1>
	</div>
</template>

<script>
	export default {
		name: 'Banner'
	}
</script>

<style scoped>
	#main-barner {
		background-image: url('/img/burger.jpg');
		background-position: 0;
		background-size: cover;
		display: flex;
		height: 500px;
		align-items: center;
		justify-content: flex-start;
	}

	#main-barner h1 {
		color: #FFF;
		text-align: center;
		font-size: 60px;
		background-color: #222;
		padding: 20px 40px;
	}
</style>