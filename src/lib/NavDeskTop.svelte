<script>
	import { navData } from '$lib/nav-data';
</script>

<nav>
	<ul class="flex gap-6">
		{#each navData as nav}
			<li class="text-white">
				<a href={nav.path}>{nav.title}</a>
			</li>
		{/each}
	</ul>
</nav>
