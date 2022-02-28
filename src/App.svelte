<script lang="ts">
  import TailwindCss from './lib/TailwindCSS.svelte'

  import Header from './lib/Header.svelte'
  import Timers from './lib/Timers.svelte'
  import Footer from './lib/Footer.svelte'
</script>

<main class="flex flex-col justify-center items-center bg-gray-900 h-full p-4 text-slate-200">
  <TailwindCss />

  <Header />

  <Timers />

  <Footer />

</main>

<style></style>
