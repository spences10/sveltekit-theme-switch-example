<script lang="ts">
	const themes = [
		'acid',
		'aqua',
		'autumn',
		'black',
		'bumblebee',
		'business',
		'cmyk',
		'coffee',
		'corporate',
		'cupcake',
		'cyberpunk',
		'dark',
		'dracula',
		'emerald',
		'fantasy',
		'forest',
		'garden',
		'halloween',
		'lemonade',
		'light',
		'lofi',
		'luxury',
		'night',
		'pastel',
		'retro',
		'synthwave',
		'valentine',
		'winter',
		'wireframe',
	]
</script>

<div class="mb-8">
	<select
		data-choose-theme
		class="select select-bordered select-primary w-full max-w-3xl text-xl capitalize"
	>
		<option disabled selected>Choose a theme</option>
		{#each themes as theme}
			<option value={theme} class="capitalize">{theme}</option>
		{/each}
	</select>
</div>
