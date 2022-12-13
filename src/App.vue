<template>
  <div id="page">
    <div id="navigation" class="container-fluid">
      <div class="row">
        <div class="col animate__animated animate__fadeInUp"><router-link to="">Home</router-link></div>
        <div class="col animate__animated animate__fadeInUp"><router-link to="">About</router-link></div>
        <div class="col animate__animated animate__fadeInUp"><router-link to="">Resume</router-link></div>
        <div class="col animate__animated animate__fadeInUp"><router-link to="">Projects</router-link></div>
        <div class="col animate__animated animate__fadeInUp"><router-link to="">Testimonials</router-link></div>
        <div class="col animate__animated animate__fadeInUp"><router-link to="">Contact</router-link></div>
      </div>
    </div>
    <div id="landing" class="container-fluid">
      <div id="titlebox">
        <div class="row animate__animated animate__fadeInDown">
           <h2>Clayton Adonis</h2>
           <h1>Aspiring Developer</h1>
        </div>
        <div id="border" class="row animate__animated animate__fadeInLeft"></div>
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
}

#titlebox {
  margin: auto;
}

#border {
  margin: auto;
  width: 50vw;
  border-bottom: solid #fcf9f2 5px;
}
</style>