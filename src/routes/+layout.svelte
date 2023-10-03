<script>
  import "../app.css";
</script>

<!-- wrapper for the website -->
<header class="container">
  <nav>
    <ul>
        <li>
            <strong>
                <a href="/">erklabs</a>
            </strong>
        </li>
    </ul>
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/about">About</a></li>
      <li><a href="/projects">Projects</a></li>
      <li><a href="/contact">Contact</a></li>
    </ul>
  </nav>
</header>

<main class="container">
  <slot />
</main>

<footer class="container">
  This is the footer.
</footer>

<style>

</style>