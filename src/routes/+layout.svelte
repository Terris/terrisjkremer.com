<script>
	import './styles.css';
</script>

<div class="app">
	<header class="header">
		<div class="wrapper">
			<h1 class="logo"><a href="/">Terris James Kremer</a></h1>
		</div>
	</header>

	<main>
		<slot />
	</main>

	<footer class="footer">
		<div class="wrapper wrapper-lg">
			<p class="copyright">&copy; 2023 Terris James Kremer</p>
		</div>
	</footer>
</div>

<style>
	.header {
		padding: 2rem 0;
	}
	.logo {
		padding-top: 0;
		font-size: 1rem;
		font-weight: 700;
	}
	.logo a {
		color: #fff;
	}
	.logo a:hover {
		color: #f1c14d;
	}
	.footer {
		font-size: 0.8rem;
		color: #5c5c5c;
		padding-bottom: 1rem;
	}
</style>
