<script>
  import { page } from '$app/stores'
  let navVisible = false

  function toggleNav() {
    navVisible = !navVisible
  }
</script>

<nav class="navbar">
  <div class="navbar-brand">
    <a class="navbar-item" class:is-actived={$page.url.pathname == '/'} href="/">Home - Wā Kāinga </a>
    <!-- only visible on mbile. when clicked, it will show the menu -->
    <a class="navbar-burger" on:click={toggleNav}>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div class="navbar-menu" class:is-active={navVisible}>
    <div class="navbar-end">
      <a class=" navbar-item" class:is-actived={$page.url.pathname == '/acts'} href="/acts">Acts - Purei</a>
      <a class="navbar-item" class:is-actived={$page.url.pathname == '/accommodation'} href="/accommodation">Accommodation - Wāhi Noho</a>
      <a class="navbar-item" class:is-actived={$page.url.pathname == '/ticket'} href="/ticket">Tickets - Tīketi </a>
    </div>
  </div>
</nav>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Rock+Salt&display=swap');
  nav {
    background-color: rgb(16, 218, 243);
  }

  a.navbar-item {
    color: black;
    font-family: 'Krona One', sans-serif;
    font-size: large;
    font-weight: 800;
    margin-right: 30px;
  }

  a.navbar-item:hover {
    background-color: rgb(16, 218, 243);
  }

  .navbar-end {
    gap: 4rem;
  }

  .navbar-menu {
    background-color: rgb(16, 218, 243);
  }
  .is-actived {
    border-radius: 15px;
    background-color: rgb(246, 123, 69);
  }

  @media screen and (max-width: 600px) {
    a.navbar-item {
      font-size: xx-small;
    }
  }
</style>
