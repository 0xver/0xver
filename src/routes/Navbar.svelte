<script>
	import logo from "$lib/images/logo.svg";
</script>

<header>
	<div class="container">
		<img src={logo} class="logomark" alt="logo" />
		<p class="wordmark">0xver</p>
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	.container {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		padding: 20px;
		width: 100%;
	}

	.logomark {
		height: 56px;
		pointer-events: none;
		margin-right: 12px;
	}

	.wordmark {
		font-size: 72px;
		font-weight: 500;
		color: #7b00ff;
		margin-left: 12px;
	}
</style>
