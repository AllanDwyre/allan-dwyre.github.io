<script>
	import Welcome from "$lib/vitest-examples/Welcome.svelte";

</script>
<header>
	<div class="row">
		<h1 style="color: #C73446; font-weight: bold;">
			Passionate about building
			<i>AI models</i>
			and deploying them.
		</h1>
		<div>
			<img src="" alt="" />
			<div class="links">
				<a href="https://www.github.com/allan-dwyre">github</a>
				<a href="https://www.linkedin.com/in/allan-dwyre/">linkeding</a>
				<a href="mail:allan.dwyre@gmail.com">mail</a>
				<a href="mail:allan.dwyre@gmail.com">cv</a>
			</div>
		</div>
	</div>

	<div class="row">
		<div class="col">
			<span>icon</span>
			<b>Recent Experience</b>
			<small>AI Engineer Internship at VIDAL France</small>
		</div>
		<div class="col">
			<span>icon</span>
			<b>Location</b>
			<small>Paris, France</small>
		</div>
	</div>
</header>

<nav>
	<a href="#experiments"> <span>icon</span> Experiments</a>
	<a href="#articles"> <span>icon</span> Blog & Articles</a>
	<a href="#diplomas"> <span>icon</span> Diplomas</a>
</nav>

<Welcome>{ host = 'SvelteKit', guest = 'Vitest' }
</Welcome>