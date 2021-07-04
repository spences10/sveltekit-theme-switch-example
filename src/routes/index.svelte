<script>
  import ThemeSelect from '$lib/theme-select.svelte'
</script>

<h1>SvelteKit Theme Switch</h1>

<p>
  This is using the <a href="https://github.com/saadeghi/theme-change"
    ><code>theme-change</code></a
  >
  package with <a href="https://daisyui.com/">DaisyUI</a>.
</p>

<p>Typography is with the Tailwind Typography package.</p>

<p>Default theme is set to light.</p>

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
