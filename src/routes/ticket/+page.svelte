<script>
  import Header from '$lib/Header.svelte'
  import Nav from '$lib/Nav.svelte'
  import Footer from '$lib/Footer.svelte'
  import Subheading from '$lib/Subheading.svelte'
  import Image from '$lib/Image.svelte'
</script>

<Nav />
<Header />
<Subheading caption="Tickets - Tīketi" />

<main>
  <Image src="/aranxa-esteve.jpg" alt="group of girls siiting in the back of the crowd" title="Aranxa Esteve" />
  <p>Tickets are $200 per person, and festival goers must be 15 years of age or older. Tent sites are $15 per night, or $40 with a tent included.</p>
  <p>Nā te tangata kotahi te utu mō ngā tīkiti, ā, me noho mā te tangata tekau mā rima tau rānei te āhua o te tangata.He $15 te utu mō ngā wāhanga papa, i te pōturi, rānei $40 me te papa whakauru.</p>
  <Image src="/hanny-naibaho.jpg" alt="large crowd of people cherring towads stage with purple lights" title="Hanny Naibaho" />
</main>
<Footer />

<style>
  @import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Rock+Salt&display=swap');
  main {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }

  p {
    font-family: 'Krona One', sans-serif;
    font-weight: 800;
    padding-top: 20px;
    color: black;
    padding: 30px;
    align-self: center;
  }

  @media screen and (max-width: 600px) {
    main {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    p {
      font-weight: 500;
      padding: 15px;
    }
  }
</style>
