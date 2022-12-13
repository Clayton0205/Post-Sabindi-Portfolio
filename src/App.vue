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
          <div id="aboutHeading">
            <h1>About Me</h1>
          </div>
          <div id="aboutDescription">
            <p>I'm caring guy who,once I've found something I'm passionate about,pursues it and my latest
              passion,coding.
              I've always enjoyed working with computers, and after a long journey of discovering myself, I realised
              that
              I'd enjoy a life of programming and development</p>
          </div>
          <div id="bioTitle">
            <h3>Bio</h3>
          </div>
          <div id="bioDescription">
            <p>I enjoy reading,playing games and watching anything with an amazing story. If I'm not coding I'm usually
              getting into long and drawn out stories. This goes for Movies,Series,Anime,Manga,Books,Light Novels and
              Games. I especially enjoy League of Legends and Legends of Runeterra because they have expansive stories
              that take place in the same universe. Riot Games has made Comics,Short Stories,Videos and a Netflix series
              on their characters making it more enjoyable for me to continue my addiction even when I'm not playing
              games</p>
          </div>
        </div>
        <div class="col">
          <img id="picture" src="https://i.postimg.cc/X7XwdBjM/1669108884251.jpg">
        </div>
      </div>
      <div id="softSkills" class="row">
        <table>
          <div id="softSkillsTitle">
            <h3>Soft Skills</h3>
          </div>
          <tr>
            <td>Decision-making <i class="fa-solid fa-house"></i></td>
            <td>Organisational</td>
            <td>Adaptability1</td>
            <td>Opennes to Criticism</td>
            <td>Writing Skills</td>
            <td>Resourcefulness</td>
          </tr>
          <tr>
            <td>Storytelling</td>
            <td>Listening</td>
            <td>Creativity</td>
            <td>Artistic Aptitude</td>
            <td>Critical Observation</td>
            <td>Public Speaking</td>
          </tr>
        </table>
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
  height: 200vh;
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

#aboutDescription {
  padding-left: 10vh;
  text-align: center;
  font-size: 3vh;
}

#bioTitle {
  margin: auto;
  width: 10vw;
  padding-top: 10vh;
  font-size: 3vh;
  border-bottom: solid #8a5649 2px;
}

#bioDescription {
  padding-left: 10vh;
  font-size: 20px;
}

#softSkills {
  text-align: center;
  margin-top: 10vh;
  margin-left: 2vw;
  margin-right: 2vw;
}

table {
  border: solid #8a5649 2px;
}

td {
  height: 20vh;
  border: solid #8a5649 1px;
}

</style>