<script>
</script>

<header>
	<div class="row header">
		<h1>
			Passionate about building
			<i style="font-family: $font-main">AI models</i>
			and deploying them.
		</h1>
		<div class="profil">
			<img src="profil.png" alt="profil" />
			<div class="links">
				<a href="https://www.github.com/allandwyre" target="_blank">
					<img src="icons/github.svg" alt="GitHub" />
				</a>
				<a href="https://www.linkedin.com/in/allan-dwyre/" target="_blank">
					<img src="icons/linkedin.svg" alt="" />
				</a>
				<a href="mailto:allan.dwyre@gmail.com?subject=Contact">
					<img src="icons/lucide_mail.svg" alt="" />
				</a>
				<a href="/cv"><img src="icons/lucide_file-text.svg" alt="cv" /></a>
			</div>
		</div>
	</div>

	<div class="row basic_info">
		<div class="col">
			<img src="icons/lucide_laptop.svg" alt="laptop" />
			<b>Recent Experience</b>
			<small>AI Engineer Internship at VIDAL France</small>
		</div>
		<div class="col">
			<img src="icons/lucide_map-pin-house.svg" alt="map pin house" />
			<b>Location</b>
			<small>Paris, France</small>
		</div>
	</div>
	<nav>
		<a href="#experiments"> <img src="icons/lucide_library-big.svg" alt="icon" /> Experiments</a>
		<a href="#articles"> <img src="icons/lucide_leafy-green.svg" alt="icon" /> Blog & Articles</a>
		<a href="#diplomas"> <img src="icons/lucide_graduation-cap.svg" alt="icon" /> Diplomas</a>
	</nav>
</header>

<style lang="scss">
	/* Add your styles here */
	img {
		width: 22px;
	}

	header {
		padding: 90px 110px;
		h1 {
			font-family: $font-heading;
			color: $primary-color;
		}
	}

	nav {
		display: flex;
		justify-content: center;
		align-items: center;

		width: fit-content;
		border-radius: 7px;
		border: 1px solid #cdcdcd;
		gap: 2rem;
		padding: 1rem 0;
		background-color: white;

		box-shadow: 0 4px 5.5px rgba(#a7a7a7, 0.25);

		a {
			text-decoration: none;
			font-weight: 600;

			&:hover {
				color: $secondary-color;
			}
		}
	}
	.header {
		width: 100%;
		justify-content: space-between;
		h1 {
			width: 40%;
			font-size: 4rem;
		}
	}
	.profil {
		display: flex;
		flex-direction: column;
		align-items: center;
		padding-right: 4rem;
		width: fit-content;

		gap: 1rem;
		> img {
			width: 30%;
			aspect-ratio: 1;
			border-radius: 50%;
			object-fit: cover;
		}

		a > img {
			&:hover {
				transform: scale(1.2);
			}
		}
	}

	.basic_info {
		gap: 2rem;
		padding: 4rem 0;
	}
</style>
