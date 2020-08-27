<script>
  import { url } from "@sveltech/routify";
</script>

<style>
  p {
    @apply text-gray-600 text-sm;
  }

  main {
    @apply text-center p-1 max-w-xs my-0 mx-auto;
  }
</style>

<main>
  <h1 class="text-4xl text-red-600 uppercase">Page not found</h1>
  <a href={$url('/')}>Return to main page</a>
</main>
