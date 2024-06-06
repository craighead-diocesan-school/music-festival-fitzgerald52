<script>
  export let title
  export let alt
  export let src
</script>

<article>
  <img class="photo" {src} {alt} {title} />
</article>

<style>
  .photo {
    margin: 20px;
    width: 650px;
    padding: 30px;
    border-radius: 15px;
    background-color: rgb(246, 123, 69, 0.5);
  }
  @media screen and (max-width: 600px) {
    .photo {
      margin: 10px;
      width: 350px;
      padding: 15px;
    }
  }
</style>
