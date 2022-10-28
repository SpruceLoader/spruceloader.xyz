<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Metadata from "$lib/Metadata.svelte";
</script>

<Metadata title="Home" description="Coming soon..." />

<div class="content">
	<img class="logo" src="favicon.png" alt="Spruce Logo" />
	<h1 class="title">Coming soon...</h1>
	<ul class="links">
		<li class="links-item"><a href="https://discord.gg/s74gCcUvhM">Discord</a></li>
		<li class="links-item"><a href="https://github.com/SpruceLoader">GitHub</a></li>
		<li class="links-item"><a href="https://twitter.com/SpruceLoader">Twitter</a></li>
	</ul>
</div>

<style>
	:global(main) {
		width: 100%;
		height: 100%;
	}

	.content {
		width: 100%;
		height: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
	}

	.logo {
		height: 200px;
	}

	.title {
		color: var(--text);
		margin: 0;
	}

	.links {
		list-style: none;
		display: flex;
		flex-direction: row;
	}

	.links-item {
		padding: 15px;
		padding-top: 0;
	}
</style>
