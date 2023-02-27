<script>
	import Footer from "./Footer.svelte";
	import Navbar from "./Navbar.svelte";
	import "./styles.css";
</script>

<div>
	<Navbar />

	<main>
		<slot />
	</main>

	<Footer />
</div>
