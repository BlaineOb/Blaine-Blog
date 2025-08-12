<script>
	import '../app.css';
</script>

<div>
	<h1>
		<a class="title" href="/">Blaine's Blog</a> <a href="/about">About</a>
	</h1>
	<slot />
</div>

<style>
	h1 {
		margin-top: 20px;
		margin-left: var(--default-margin);
		font-size: 2.5rem;
	}

	a {
		text-decoration: none;
		color: #1db954;
		font-size: 1.25rem;
	}

	a:hover {
		color: darkgray;
	}

	.title {
		margin-top: 20px;
		font-size: 2.5rem;
	}
</style>
