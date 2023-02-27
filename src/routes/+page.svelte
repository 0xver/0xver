<script>
	import Title from "./components/Title.svelte";
	import Node from "./components/Node.svelte";
	import Python from "./components/Python.svelte";
	import GitHub from "./components/GitHub.svelte";
</script>

<svelte:head>
	<title>0xver</title>
	<meta name="description" content="0xver" />
</svelte:head>

<section>
	<div class="main">
		<div class="container">
			<Title />
			<Node />
			<Python />
			<GitHub />
		</div>
	</div>
</section>

<style>
	.main {
		text-align: center;
		width: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: top;
		font-size: calc(10px + 2vmin);
		max-width: 600px;
		color: #c9d1d8;
	}
</style>
