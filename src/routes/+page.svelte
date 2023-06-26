<script>
	import ThemeSelect from '$lib/theme-select.svelte'
</script>

<h1>SvelteKit Theme Switch</h1>

<p>
	This is using a <a
		href="https://scriptraccoon.dev/blog/darkmode-toggle-sveltekit#bonus"
	>
		cookie based theme change
	</a>
	with <a href="https://daisyui.com/">daisyUI</a> for the themes.
</p>

<p>Typography is with the Tailwind Typography package.</p>

<p>Default theme is set to dark.</p>

<ThemeSelect />

<p>Here's some DaisyUI buttons, yummy!</p>

<button class="btn">neutral</button>
<button class="btn btn-primary">primary</button>
<button class="btn btn-secondary">secondary</button>
<button class="btn btn-accent">accent</button>
<button class="btn btn-ghost">ghost</button>
<button class="btn btn-link">link</button>

<p>
	Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the
	documentation
</p>
