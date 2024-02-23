<template>
  <div class="main-container">
    <div class="container1">
      <div class="profile">
        <img src="../assets/perfil.peg.jpeg" alt="" width="200px" />
        <h3>Vicente Avilés</h3>
        <p>Software Developer</p>
      </div>
      <div class="social-links">
        <div class="link-div">
          <a href="https://github.com/MONTAR0N">
            <img src="../assets/github-logo-icon.png" alt="" class="logo-img" />
            <h3>Github</h3>
          </a>
        </div>
        <div class="link-div">
          <a href="https://www.linkedin.com/in/vicente-avil%C3%A9s-93a63b171/">
            <img
              src="../assets/icons8-linkedin-48.png"
              alt=""
              class="logo-img"
            />
            <h3>LinkedIn</h3>
          </a>
        </div>
        <div class="link-div">
          <a href="mailto:vavilesb1@gmail.com">
            <img src="../assets/gmail-logo-4-1.png" alt="" class="logo-img" />
            <h3>Gmail</h3>
          </a>
        </div>
        <div class="link-div">
          <a href="https://wa.me/56977556547">
            <img
              src="../assets/whatsapp-logo-4-1.png"
              alt=""
              class="logo-img"
            />
            <h3>WhatsApp</h3>
          </a>
        </div>
      </div>
    </div>

    <div class="container2">
      <div class="about">
        <h1>About me</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae
          omnis delectus blanditiis reiciendis error veritatis suscipit
          consequatur eius autem aut necessitatibus corporis velit, facilis enim
          obcaecati. Voluptatem accusamus totam corporis.
        </p>
      </div>
      <div class="technology-section">
        <h1>Languages and Tools</h1>
        <p>
          <a href="https://www.w3schools.com/css/" target="_blank">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg"
              alt="css3"
              width="40"
              height="40"
            />
          </a>
          <a href="https://expressjs.com" target="_blank">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg"
              alt="express"
              width="40"
              height="40"
            />
          </a>
          <a href="https://es.react.dev/" target="_blank">
            <img
              src="https://www.vectorlogo.zone/logos/reactjs/reactjs-icon.svg"
              alt="react"
              width="40"
              height="40"
            />
          </a>
          <a href="https://es.redux.js.org/" target="_blank">
            <img
              src="https://www.svgrepo.com/show/303557/redux-logo.svg"
              alt="redux"
              width="40"
              height="40"
            />
          </a>
          <a href="https://www.w3.org/html/" target="_blank">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg"
              alt="html5"
              width="40"
              height="40"
            />
          </a>
          <a
            href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"
            target="_blank"
          >
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg"
              alt="javascript"
              width="40"
              height="40"
            />
          </a>
          <a href="https://nodejs.org" target="_blank">
            <img
              src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg"
              alt="nodejs"
              width="40"
              height="40"
            />
          </a>
          <a href="https://vuejs.org//" target="_blank">
            <img
              src="https://www.vectorlogo.zone/logos/vuejs/vuejs-icon.svg"
              alt="Vue.js"
              width="40"
              height="40"
            />
          </a>
          <a href="https://sequelize.org/" target="_blank">
            <img
              src="https://www.vectorlogo.zone/logos/sequelizejs/sequelizejs-icon.svg"
              alt="sequelize"
              width="40"
              height="40"
            />
          </a>
          <a href="https://www.postgresql.org/" target="_blank">
            <img
              src="https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg"
              alt="postgreSQL"
              width="40"
              height="40"
            />
          </a>
        </p>
      </div>

      <div class="buttonContainer">
        <div class="button">
          <a href="">
            <h2>My Proyects</h2>
          </a>
        </div>
        <div class="button">
          <a href="">
            <h2>My Resumé</h2>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.logo-img {
  height: auto;
  width: 40px;
}
.main-container {
  display: flex;
  background-color: black;
  margin: 5%;
  border-radius: 20px;
  /* flex-direction: column; */
  /* align-items: center; */
}
.container1 {
  background-color: rgb(245, 243, 128);
  width: 25%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 3rem;
  flex-direction: column;
  margin: 5px;
  border-radius: 20px;
}
.container1 a {
  text-decoration: none;
}
.container2 {
  display: flex;
  background-color: rgb(235, 250, 191);
  color: rgb(0, 0, 0);
  width: 75%;
  flex-direction: column;
  align-items: center;
  padding: 3rem;
  justify-content: space-evenly;
  border-radius: 20px;
  margin: 5px;
}

.container2 a {
  text-decoration: none;
}
.profile img {
  width: 6rem;
  border-radius: 10px;
}
.about {
  display: flex;
  align-items: center;
  flex-direction: column;
  text-align: left;
}

.buttonContainer {
  display: flex;
  flex-direction: row;
}
.button {
  border: solid black 1px;
  margin: 10px;
  padding-left: 5px;
  padding-right: 5px;
  border-radius: 20px;
  background-color: rgb(226, 243, 42);
}

/* .about p{
  display: flex;
} */

.technology-section {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
