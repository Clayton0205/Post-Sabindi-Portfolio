<template>
  <div id="page">
    <div id="navigation" class="container-fluid">
      <div class="row">
        <div class="col animate__animated animate__fadeInUp"><a href="#landing">Home</a></div>
        <div class="col animate__animated animate__fadeInUp"><a href="#about">About</a></div>
        <div class="col animate__animated animate__fadeInUp"><a href="">Resume</a></div>
        <div class="col animate__animated animate__fadeInUp"><a href="">Projects</a></div>
        <div class="col animate__animated animate__fadeInUp"><a href="">Testimonials</a></div>
        <div class="col animate__animated animate__fadeInUp"><a href="">Conatct</a></div>
      </div>
    </div>
    <div id="landing" class="container-fluid">
      <div id="titlebox">
        <div id="titlewords" class="row animate__animated animate__fadeInDown">
          <h2>Clayton Adonis</h2>
          <h1>Aspiring Developer</h1>
        </div>
        <div id="border" class="row animate__animated animate__fadeInLeft"></div>
      </div>
    </div>
    <div id="about" class="container-fluid">
      <div class="row">
        <div class="col">
          <div id="aboutHeading"><h1>About Me</h1></div>
          <div id="aboutDescription"><p>I'm caring guy who,once I've found something I'm passionate about,pursues it and my latest passion,coding.
          I've always enjoyed working with computers, and after a long journey of discovering myself, I realised that
          I'd enjoy a life of programming and development</p></div>
        </div>
        <div class="col">
          <img id="picture" src="https://i.postimg.cc/X7XwdBjM/1669108884251.jpg">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

#page {
  font-family: 'PT Serif', serif;
  overflow-x: hidden;
  scroll-behavior: smooth;
}

#navigation {

  background: transparent;
  text-align: center;
  width: 100vw;
  height: 100vh;
  position: fixed;
}

a {
  color: #e4b998;
  text-decoration: none;
}

#landing {
  background-image: radial-gradient(circle, #c49b84, #b58974, #a77865, #986757, #8a5649);
  color: #fcf9f2;
  width: 100vw;
  height: 100vh;
  padding-top: 45vh;
  text-align: center;
  border-bottom: double #c49b84 5px;
  ;
}

#titlebox {
  margin: auto;
  width: 50vw;
}

#titlewords {
  border-top: solid #fcf9f2 5px;
  border-left: solid #fcf9f2 5px;
  border-right: solid #fcf9f2 5px;
}

#border {
  margin: auto;
  border-bottom: solid #fcf9f2 5px;
}

#about {
  background-image: linear-gradient(to bottom, #fcf9f2, #f4eada, #eddac2, #e8caac, #e4b998);
  color: #8a5649;
  padding-top: 5vh;
  text-align: center;
  width: 100vw;
  height: 100vh;
  border-bottom: double #c49b84 5px;
}

#picture {
  padding-top: 10vh;
  width: 25vw;
  height: 80vh;
}

#aboutHeading {
  margin: auto;
  width: 20vw;
  border-bottom: solid #8a5649 3px;
}

/* #aboutDescription {

} */
</style>