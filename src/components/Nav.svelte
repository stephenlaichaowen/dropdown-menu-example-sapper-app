<script>
  export let segment;
  let highlight = false
</script>

<nav class="navbar navbar-expand-sm navbar-light bg-light">
  <a class="navbar-brand" href="/">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav ml-auto">
      <a aria-current='{segment === undefined ? "page" : undefined}' class="nav-item nav-link" href="/">Home <span class="sr-only">(current)</span></a>
      <a aria-current='{segment === "features" ? "page" : undefined}' class="nav-item nav-link" href="/features">Features</a>
      <a aria-current='{segment === "pricing" ? "page" : undefined}' class="nav-item nav-link" href="/pricing">Pricing</a>    
    </div>
  </div>
</nav>

