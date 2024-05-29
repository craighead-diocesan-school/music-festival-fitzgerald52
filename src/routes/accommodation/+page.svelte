<script>
  import Header from '$lib/Header.svelte'
  import Nav from '$lib/Nav.svelte'
  import Footer from '$lib/Footer.svelte'
</script>

<Nav />
<Header />
<h2>accommodation</h2>
<main>
  <img class="photo" src="/tony-pham.jpg" alt="" />
  <p>Experience the ultimate music festival adventure with our tent accommodation packages! With our comfortable and convenient tents, you can immerse yourself in the festival atmosphere and stay close to all the action. Our tents are spacious and come equipped with everything you need for a comfortable stay. With comfortable beds, pillows, and blankets, you can get a good night's sleep and wake up feeling refreshed and ready for another day of music and fun. Located within the festival grounds, our tents are just a short walk away from all the stages and attractions. You won't have to worry about transportation or navigating crowds to get to the festival – you'll be right in the heart of it all.</p>
  <p>Our tents also come with a range of amenities to make your stay even more comfortable. You'll have access to clean restroom facilities, hot showers, and charging stations for your devices. We also have a dedicated staff available to assist with any needs or questions you may have during your stay. But the best part of our tent accommodation packages is the community. You'll be surrounded by other festival-goers who are just as excited as you are to be a part of the experience. You'll make new friends, share stories, and create memories that will last a lifetime. Don't miss out on this opportunity to enhance your music festival experience. Book your tent accommodation package today and get ready for an unforgettable adventure. We can't wait to see you there!</p>
  <img class="photo" src="/krists-luhaers.jpg" alt="" />
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
  }
  .photo {
    width: 650px;
    padding: 30px;
  }
</style>
