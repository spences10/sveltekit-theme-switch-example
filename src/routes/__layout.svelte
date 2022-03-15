<script>
  import { onMount } from 'svelte'
  import { themeChange } from 'theme-change'
  import '../app.css'

  onMount(() => {
    themeChange(false)
  })
</script>

<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
  <div class="max-w-3xl mx-auto prose md:prose-lg lg:prose-xl">
    <main>
      <slot />
    </main>
  </div>
</div>
