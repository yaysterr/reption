<script>
  let imageSrc = "/G2white.png";
</script>

<style>
  img {
    width: 8rem;
    height: auto;
    transition: opacity 0.5s ease-in-out, transform 0.3s ease-in-out;
  }
  img:hover {
    transform: scale(1.05);
  }
</style>
<div class="flex flex-col items-center justify-center h-screen">
  <div class="">
    <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0" >
      <img
        class="w-32 h-auto cursor-pointer"
        src={imageSrc}
        alt=""
        on:mouseenter={() => (imageSrc = "/G2.svg")}
        on:mouseleave={() => (imageSrc = "/G2white.png")}
      />
    </a>
  </div>
  <div class="mt-4">
    <p>Welcome to kan's webpage</p>
    <p>Nothing's here to be honest</p>
  </div>
</div>
<div class="h-screen">
</div>
<div class="h-screen">
</div>
<div class="flex flex-col items-center cursor-pointer">
  <a href="https://www.instagram.com/p/DJeSHzZJ0T8/">
    <img src="/g2-g2win.gif" alt="">
  </a>
</div>