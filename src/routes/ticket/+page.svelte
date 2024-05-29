<script>
  import Header from '$lib/Header.svelte'
  import Nav from '$lib/Nav.svelte'
  import Footer from '$lib/Footer.svelte'
</script>

<Nav />
<Header />
<h2>tickets</h2>
<main>
  <img class="photo" src="/aranxa-esteve.jpg" alt="group of young adults having fun ontop of each others shoulderss" />
  <p>Tickets are $200 per person, and festival goers must be 15 years of age or older. Tent sites are $15 per night, or $40 with a tent included.</p>
  <p>Nā te tangata kotahi te utu mō ngā tīkiti, ā, me noho mā te tangata tekau mā rima tau rānei te āhua o te tangata.He $15 te utu mō ngā wāhanga papa, i te pōturi, rānei $40 me te papa whakauru.</p>
  <img class="photo" src="/hanny-naibaho.jpg" alt="large crowd of people cherring towads stage while confitie falls" />
</main>
<Footer />

<style>
  @import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Rock+Salt&display=swap');
  main {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  h2 {
    background-color: rgb(249, 125, 193);
    padding: 20px;
    font-size: x-large;
    color: black;
    text-align: center;
    font-family: 'Rock Salt', cursive;
    font-weight: 800;
  }
  p {
    font-family: 'Krona One', sans-serif;
    font-weight: 800;
    padding-top: 20px;
    color: black;
    padding: 30px;
    align-self: center;
  }
  .photo {
    width: 650px;
    padding: 30px;
  }
</style>
