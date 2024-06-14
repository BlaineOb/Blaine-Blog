<script>
	import '../app.css'
</script>

<style>
	h1 {
			margin-top: 20px;
			font-size: 2.5rem;
	}

	a {
			text-decoration: none;
			color: white;
			font-size: 1.25rem;
	}

	a:hover{
      color: darkgray;
  }

	div {
      margin-left: 20%;
	}

	.title {
      margin-top: 20px;
      font-size: 2.5rem;
	}
</style>

<div>
	<h1>
		<a class="title" href="/">Blaine's Blog</a> <a href="/links">Links</a>
	</h1>
	<slot />
</div>
