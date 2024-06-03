<script>
  import { page } from '$app/stores'
</script>

<nav>
  <a class:is-active={$page.url.pathname == '/'} href="/">Home - Wā Kāinga </a>
  <a class:is-active={$page.url.pathname == '/acts'} href="/acts">Acts - Purei</a>
  <a class:is-active={$page.url.pathname == '/accommodation'} href="/accommodation">Accommodation - Wāhi Noho</a>
  <a class:is-active={$page.url.pathname == '/ticket'} href="/ticket">Tickets - Tīketi </a>
</nav>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Rock+Salt&display=swap');
  nav {
    background-color: rgb(16, 218, 243);
    padding: 25px;
    display: flex;
    justify-content: space-around;
  }
  a {
    padding-left: 50px;
    padding-right: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    color: black;
    font-family: 'Krona One', sans-serif;
    font-size: large;
    font-weight: 800;
  }
  .is-active {
    border-radius: 15px;
    background-color: rgb(246, 123, 69);
  }
</style>
