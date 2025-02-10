<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
	<div class="prose md:prose-lg lg:prose-xl mx-auto max-w-3xl">
		<main>
			{@render children()}
		</main>
	</div>
</div>
