<script>
  import ThemeSelect from '$lib/theme-select.svelte'
  import { onMount } from 'svelte'
  import { themeChange } from 'theme-change'
  import '../app.postcss'

  onMount(async () => {
    themeChange(false)
  })
</script>

<main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
  <div class="max-w-3xl mx-auto">
    <ThemeSelect />
    <slot />
  </div>
</main>
