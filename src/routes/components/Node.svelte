<div class="container">
	<div class="header">
		<p>Node Packages</p>
		<p>Installation</p>
	</div>
	<div class="packages">
		<p>Shell</p>
		<!-- svelte-ignore security-anchor-rel-noreferrer -->
		<a href="https://github.com/0xver/shell" target="_blank">
			<code class="install">npm i -g @0xver/shell</code>
		</a>
	</div>
	<div class="packages">
		<p>Solver</p>
		<!-- svelte-ignore security-anchor-rel-noreferrer -->
		<a href="https://github.com/0xver/solver" target="_blank">
			<code class="install">npm i -D @0xver/solver</code>
		</a>
	</div>
	<div class="packages">
		<p>Hardhat</p>
		<!-- svelte-ignore security-anchor-rel-noreferrer -->
		<a href="https://github.com/0xver/hardhat" target="_blank">
			<code class="install">gh repo clone 0xver/hardhat</code>
		</a>
	</div>
	<div class="packages">
		<p>Svelte</p>
		<!-- svelte-ignore security-anchor-rel-noreferrer -->
		<a href="https://github.com/0xver/svelte" target="_blank">
			<code class="install">gh repo clone 0xver/svelte</code>
		</a>
	</div>
</div>

<style>
	.container {
		padding-top: 15px;
		padding-bottom: 20px;
		padding-right: 20px;
		padding-left: 20px;
		border: 0.5px solid;
		border-color: #373b40;
		width: 90%;
		margin-bottom: 20px;
		font-size: calc(9px + 1vmin);
		text-align: left;
	}

	.header {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
		margin-bottom: 15px;
	}

	.packages {
		font-size: calc(10px + 2vmin);
		padding-top: 10px;
		padding-bottom: 10px;
		padding-right: 10px;
		padding-left: 20px;
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: space-between;
		margin-bottom: 15px;
		border-radius: 100px;
		background-color: #14181f;
	}

	.install {
		font-size: calc(9px + 1vmin);
		text-align: center;
		display: flex;
		padding-top: 5px;
		padding-bottom: 5px;
		padding-right: 10px;
		padding-left: 10px;
		background-color: #252c38;
		border-radius: 100px;
		cursor: pointer;
	}

	.install:hover {
		background-color: #212732;
	}

	.install {
		font-size: calc(9px + 1vmin);
		text-align: center;
		display: flex;
		padding-top: 5px;
		padding-bottom: 5px;
		padding-right: 10px;
		padding-left: 10px;
		background-color: #252c38;
		border-radius: 100px;
		cursor: pointer;
	}

	@media only screen and (max-width: 675px) {
		.install {
			font-size: calc(7px + 1vmin);
		}
	}

	a {
		color: inherit;
		text-decoration: none;
	}
</style>
