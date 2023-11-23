<template>
  <div class="wrapper">
    <div class="main-container">
      <div class="container-one">
        <div class="profile">
          <img src="../assets/hero.webp" alt="profile" />
          <h3>Saint Hokaha</h3>
          <p>Software Developer</p>
        </div>
        <div class="social-links">
          <div class="link">
            <a href="">
              <img src="../assets/github (1).svg" alt="github" />
              <h2>Github</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/facebook (1).svg" alt="facebook" />
              <h2>Facebook</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/instagram (1).svg" alt="instagram" />
              <h2>Instagram</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/twitter.svg" alt="twitter" />
              <h2>Twitter</h2>
            </a>
          </div>
          <div class="link">
            <a href="">
              <img src="../assets/whatsapp (1).svg" alt="whatsapp" />
              <h2>WhatsApp</h2>
            </a>
          </div>
        </div>
      </div>
      <div class="container-two">
        <div class="about-me">
          <h1>About me</h1>
          <p>
            Hi there! My name is Eno, Hokaha Bassey, I am a creative and passionate
            individual with a strong work ethic and a desire to learn. I am always looking
            for new challenges and opportunities to grow and develop my skills. I am also
            a team player and I enjoy working with others to achieve common goals.<br />
            <br />I am excited to start this next chapter in my career and I look forward
            to working with new people and contributing to new projects.
          </p>
        </div>
        <div class="technology-section">
          <h1>Technologies Studied</h1>
          <div class="logos">
            <img src="../assets/html-png.webp" alt="html" />
            <img src="../assets/css.png" alt="css" />
            <img src="../assets/tailwind-css.jpeg" alt="tailwind" />
            <img src="../assets/bootstrap-logo.svg" alt="bootstrap" />
            <img src="../assets/javascript-logo.webp" alt="javascript" />
            <img src="../assets/logo.png" alt="vue.js" />
            <img src="../assets/inertia.png" alt="inertia.js" />
            <img
              src="../assets/png-transparent-deploying-node-js-website-development-javascript-web-application-vue-js-text-rectangle-logo.png"
              alt="node.js"
            />
          </div>
        </div>
        <div class="button-container">
          <div class="projects-button">
            <a href="">My Projects</a>
          </div>
          <div class="projects-button">
            <a href="">My Resume</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.wrapper {
  display: flex;
  justify-content: center;
}

img {
  height: 48px;
}

.main-container {
  margin-top: 5%;
  display: flex;
  flex-direction: row;
  background-color: #cecece;
  border-radius: 25px;
  width: 60%;
  background-color: #a0d4ff;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

.container-one {
  background-color: #1292ee;
  width: 30%;
  padding: 2.5%;
  border-radius: 25px;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

.profile img {
  height: 10rem;
  border-radius: 50%;
}

.link a {
  text-decoration: none;
  color: #2c3e50;
  font-size: 13px;
}

.link img {
  height: 3rem;
}

.container-two {
  margin: 2.5%;
  width: 70%;
}

.about-me {
  text-align: left;
}

.logos img {
  height: 3.2rem;
  padding: 7px;
}

.button-container {
  margin-top: 5%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.projects-button {
  background-color: #005ca4;
  padding: 15px;
  border-radius: 30px;
  margin: 10px;
}

.projects-button a {
  text-decoration: none;
  color: #fff;
}

@media only screen and (max-width: 950px) {
  .main-container {
    width: 95%;
  }
}
</style>
