<script>
	import './styles.css';
</script>

<div class="wrapper">
	<h2 class="hero">
		Hi, I'm Terris. I'm a <a href="https://github.com/Terris">front-end web developer</a> and
		hobbyist writer, <a href="https://www.instagram.com/terrisjameskremer/">photographer</a>, and
		musician.
	</h2>
	<nav class="nav-secondary">
		<a href="https://github.com/Terris"><i class="fab fa-github" /></a>
		<a href="https://www.linkedin.com/in/terris-kremer-828292147/"
			><i class="fab fa-linkedin-in" /></a
		>
		<a href="https://www.instagram.com/terrisjameskremer/"><i class="fab fa-instagram" /></a>
		<a href="https://dribbble.com/terrisj"><i class="fab fa-dribbble" /></a>
	</nav>
</div>

<style>
	/* Main
  ----------------------------------------------- */
	.nav-secondary a {
		display: inline-block;
		padding: 1rem 20px;
		color: #fff;
	}
	.nav-secondary a:hover {
		color: #ffe45c;
	}

	@media screen and (min-width: 820px) {
		.hero {
			width: 66.666666%;
			padding-right: 40px;
		}
	}

	/* Projects section
  ----------------------------------------------- */

	.projects .project-item .project-item-title {
		padding-bottom: 0;
		font-size: 1.15rem;
		font-weight: 400;
	}

	.projects .project-item .project-item-description {
		padding-top: 0;
		padding-bottom: 0;
	}
	.projects .project-item .project-item-links {
		padding-top: 0.5rem;
		margin-left: -20px;
	}
	.projects .project-item .project-item-links a {
		color: #fff;
		margin-left: 20px;
	}
	.projects .project-item .project-item-links a:hover {
		color: #ffe45c;
	}
	.projects .project-item .project-item-tags {
		padding-top: 0;
		padding-bottom: 0;
		font-size: 0.8rem;
		color: #5c5c5c;
	}

	@media screen and (min-width: 700px) {
		.projects {
			display: flex;
			align-items: flex-start;
			justify-content: space-between;
		}
		.projects .projects-col {
			width: 33.333333%;
			padding: 0 20px;
		}
		.projects .projects-col:first-child {
			padding-left: 0;
		}
		.projects .projects-col:last-child {
			padding-right: 0;
		}
	}
</style>
