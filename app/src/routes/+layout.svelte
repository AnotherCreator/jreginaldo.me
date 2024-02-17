<!--
  Renders the following elements on this page across all '/routes/[Route Name]/+page.svelte'
-->
<nav class="top_nav">
  <a href="/">Home</a>
  <a href="/">About</a>
  <a href="/">Projects</a>
</nav>

<style>
  .top_nav {
      text-align: center;
  }
</style>

<slot></slot>