<script lang="ts">
	import '../app.pcss';

	const { children } = $props();
</script>

<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
	<div class="prose mx-auto max-w-3xl md:prose-lg lg:prose-xl">
		<main>
			{@render children()}
		</main>
	</div>
</div>
