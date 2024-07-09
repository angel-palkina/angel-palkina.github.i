<script lang="ts">
	import Menu from '../_layout.svelte';
	import proj1 from './../../img/portfolio/project1.jpg';
	import proj2 from './../../img/portfolio/project2.jpg';
</script>

<head>
	<title>Projects</title>
	<meta
		name="description"
		content="The page with the main projects of the frontend developer (Palkina Sofia Sergeevna)"
	/>
</head>

<body>
	<div class="portfolio">
		<div class="container">
			<h1 class="portfolio-header">Projects</h1>
			<div class="portfolio-cards">
				<div class="card">
					<a href="https://github.com/angel-palkina/Schoole_Syte">
						<img class="card-image" src={proj1} alt="First website" />
					</a>
					<h3 class="card-title">First website</h3>
				</div>
				<div class="card">
					<a href="https://github.com/angel-palkina/SSAD">
						<img class="card-image" src={proj2} alt="First C++ program" />
					</a>
					<h3 class="card-title">First C++ program</h3>
				</div>
			</div>
		</div>
	</div>
</body>
<Menu />

<style>
	body {
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background-size: cover;
		background-position: center;
		font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	}
	.container {
		width: 80%;
		margin-left: auto;
		margin-right: auto;
	}
	.portfolio {
		background-image: url(./../../img/fon.jfif);
		background-size: cover;
		background-position: center;
		padding-top: 40px;
		padding-bottom: 115px;
	}

	.portfolio-header {
		font-weight: 700;
		font-size: 46px;
		line-height: 130%;
		text-align: center;
		color: #fff;
	}
	.portfolio-cards {
		display: flex;
		flex-wrap: wrap;
		justify-content: space-between;
	}
	.card {
		background-color: #ffffff;
		max-width: 540px;
		padding: 20px;
	}
	.card-image {
		margin-bottom: 20px;
		width: 100%;
		height: 80%;
	}
	.card-title {
		margin: 0;
		margin-bottom: 13px;
		font-weight: 600;
		font-size: 24px;
		line-height: 130%;
		color: #000;
	}
</style>
