<script>
  export let caption
</script>

<article>
  <h2>{caption}</h2>
</article>

<style>
  h2 {
    background-color: rgb(249, 125, 193);
    padding: 20px;
    font-size: x-large;
    color: black;
    text-align: center;
    font-family: 'Rock Salt', cursive;
    font-weight: 800;
  }
  @media screen and (max-width: 600px) {
    h2 {
      font-size: larger;
    }
  }
</style>
