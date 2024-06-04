<script>
  import Header from '$lib/Header.svelte'
  import Nav from '$lib/Nav.svelte'
  import Footer from '$lib/Footer.svelte'
</script>

<Nav />
<Header />
<h2>Home - Wā Kāinga</h2>
<main>
  <img class="photo" src="/jade-masri.jpg" alt="group of young adults having fun ontop of each others shoulderss" title="Jade Masri" />
  <p>Welcome to the ultimate music festival experience! Get ready for a day filled with live music, great food, and unforgettable memories. Our festival features a diverse lineup of talented musicians from different genres, sure to satisfy every taste in music. With multiple stages set up throughout the venue, you can easily move from one act to the next, discovering new favorites and enjoying classic hits. From up-and-coming artists to established headliners, we have curated an exciting lineup that will keep you dancing and singing along all day long. Our festival is the perfect opportunity to discover new music, see your favorite artists live, and make lasting memories with friends and family.</p>
  <p>But the music is just the beginning. Our festival also boasts an impressive selection of food vendors, offering everything from classic festival fare to more gourmet options. You won't go hungry with the delicious treats and refreshing beverages available throughout the venue. In addition to the music and food, our festival also features a variety of activities to keep you entertained throughout the day. From art installations to merchandise booths, there is something for everyone to enjoy. You can even capture the memories with our festival photo booths and snap a selfie with your favourite artists. So don't miss out on this one-of-a-kind music festival experience. Get your tickets now and join us for a day of music, fun, and community. We can't wait to see you there!</p>
  <img class="photo" src="/james-genchi.jpg" alt="large crowd of people cherring towads stage while confitie falls" title="James Genchi" />
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
    margin: 20px;
    width: 650px;
    padding: 30px;
    border-radius: 15px;
    background-color: rgb(246, 123, 69, 0.5);
  }
  @media screen and (max-width: 600px) {
    main {
      display: flex;
    }
    h2 {
      font-size: larger;
    }
    p {
      font-weight: 500;
      padding: 15px;
    }
    .photo {
      margin: 10px;
      width: 500px;
      padding: 15px;
    }
  }
</style>
