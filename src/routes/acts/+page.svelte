<script>
  import Header from '$lib/Header.svelte'
  import Nav from '$lib/Nav.svelte'
  import Footer from '$lib/Footer.svelte'
  import Subheading from '$lib/Subheading.svelte'
  import Image from '$lib/Image.svelte'
</script>

<Nav />
<Header />
<Subheading caption="Acts - Purei" />

<main>
  <Image src="/colin-lloyd.jpg" alt="lady djing " title="Colin Lloyd" />
  <p>
    The music festival boasts an exciting lineup of talented musicians from a variety of genres, promising a diverse and entertaining experience for all attendees. On the main stage, the headliners are a mix of established and up-and-coming acts, guaranteed to draw in large crowds. The first headliner is a popular rock band, known for their high-energy performances and catchy hooks. They will be followed by a chart-topping pop artist, whose upbeat and infectious hits are sure to get the crowd dancing and singing along. The final headliner is a legendary hip-hop artist, whose iconic rhymes and charismatic stage presence will bring the festival to a thrilling close. On the second stage, indie bands and singer-songwriters showcase their unique styles and sounds. The performers on this stage are often the most buzzed-about acts of the festival, with a loyal and passionate following. From dreamy shoegaze bands to alternative rock acts, the second stage offers a more intimate and personal
    experience for music lovers looking to discover new artists.
  </p>
  <p>The third stage is dedicated to up-and-coming artists from different genres, providing a platform for emerging talent to showcase their skills and gain exposure. This stage is a great opportunity for attendees to discover new artists and support the next generation of musicians. Throughout the festival, DJs and electronic acts keep the energy up between sets, playing a mix of classic and contemporary dance tracks that will keep the crowd moving and grooving. Overall, the music festival offers a diverse and exciting lineup that caters to different tastes and styles. From established headliners to emerging talent, the festival promises a memorable and thrilling musical experience for all attendees.</p>
  <Image src="/maxwell-collins.jpg" alt="man playing guitar infront of large crowd" title="Maxwell Collins" />
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
    }

    p {
      font-weight: 500;
      padding: 15px;
    }
  }
</style>
