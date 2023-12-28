<script>
	import '../app.postcss';
</script>

<svelte:head>
	<title>Matthew Wilks</title>
</svelte:head>

<section
	class="m-auto flex justify-center items-center flex-col w-screen h-screen max-w-3xl text-center gap-4"
>
	<h1>About Me</h1>
	<p>
		Hey, I'm Matthew Wilks an open source developer who loves Rust and Svelte. My most notable
		contribution to OSS would be implementing Windows sign on support for the <a
			href="https://github.com/kanidm/kanidm"
			class="link link-info"
			target="_blank">kanidm</a
		> project. However due to windows deprecating custom SSP/APs in favour of Kerberos, this contribution
		never got finished.
	</p>
	<p>
		If you ever need to contact me, you can usually find me hanging out in the openSUSE discord
		server (water261) or the openSUSE Matrix channels (@water261:matrix.org).
	</p>
</section>

<footer class="absolute bottom-0 m-1">
	Made with love using <a href="https://svelte.dev" target="_blank" class="link link-info">Svelte</a
	>
</footer>
