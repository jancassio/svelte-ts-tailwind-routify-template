<script>
  import { url } from "@sveltech/routify";
</script>

<style>
  main {
    @apply text-center p-1 max-w-xs my-0 mx-auto;
  }
</style>

<nav>
  <ul class="flex space-x-8">
    <li>
      <a href={$url('/')}>Home</a>
    </li>
    <li>
      <a href={$url('./about')}>About</a>
    </li>
    <li>
      <a href={$url('/subpage/lorem-ipsum')}>Sub page</a>
    </li>
  </ul>
</nav>

<main>
  <slot />
</main>
