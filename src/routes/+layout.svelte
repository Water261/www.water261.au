<script>
	import "../app.postcss";
</script>

<nav class="navbar shadow z-10 bg-base-100">
	<div class="flex-1">
		<a href="#top" class="btn btn-ghost normal-case text-xl hover:btn-active">Matthew Wilks</a>
		<div class="hidden lg:flex divider divider-horizontal mx-0" />
		<ul class="hidden lg:flex menu menu-horizontal py-0 gap-2">
			<li><a href="https://github.com/Water261" rel="noreferrer" target="_blank">GitHub</a></li>
		</ul>
	</div>
	<div class="flex-none">
		<details class="dropdown dropdown-end lg:hidden">
			<summary class="m-1 list-none">
				<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
					<path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
				</svg>				  
			</summary>
			<ul class="p-2 shadow menu dropdown-content z-[1] bg-base-100 rounded-box w-52 mt-6">
				<li><a href="https://github.com/Water261" rel="noreferrer" target="_blank">GitHub</a></li>	
			</ul>
		</details>
	</div>
</nav>

<main class="z-0">
	<slot />
</main>	

<style lang="postcss">
	ul.menu li a {
		@apply text-lg;
	}

	ul.menu li a:hover {
		@apply bg-base-300;
	}
</style>
