<script>
import {base} from "$app/paths";
</script>

<!--
  Renders the following elements on this page across all '/routes/[Route Name]/+page.svelte'
-->
<nav class="top_nav">

  <a href="{base}/">Home</a>
  <a href="{base}/">About</a>
  <a href="{base}/">Projects</a>
</nav>

<style>
    .top_nav {
        text-align: center;
    }
</style>

<slot></slot>