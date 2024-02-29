<template>
  <div class="wrapper">
  <div class="main-container">
    <div class="container1">
      <div class="profile">
        <img src="../assets/foto yo.PNG" alt="" width="200px" />
        <h2>Vicente Avilés</h2>
        <h3>Software Developer</h3>
      </div>
      <div class="social-links">
        <a href="https://github.com/MONTAR0N">
          <img
            src="../components/icons/icons8-github-50.png"
            alt=""
            class="logo-img"
          />
          <h3>Github</h3>
        </a>

        <a href="https://www.linkedin.com/in/vicente-avil%C3%A9s-93a63b171/">
          <img
            src="../components/icons/icons8-linkedin-50.png"
            alt=""
            class="logo-img"
          />
          <h3>LinkedIn</h3>
        </a>

        <a href="mailto:vavilesb1@gmail.com">
          <img
            src="../components/icons/icons8-mail-50 (1).png"
            alt=""
            class="logo-img"
          />
          <h3>Gmail</h3>
        </a>
        <a href="https://wa.me/56977556547">
          <img
            src="../components/icons/icons8-whatsapp-50.png"
            alt=""
            class="logo-img"
          />
          <h3>WhatsApp</h3>
        </a>
      </div>
    </div>

    <div class="container2">
      <div class="about">
        <h1>About me</h1>
        <p>
My professional journey began in the legal field, where I gained a deep understanding of strategic litigation management and the legal world in general. Additionally, I have significantly developed my soft skills. However, my passion for technology led me to embark on an exciting career as a Full Stack developer.
The fusion of my legal knowledge with development equips me to tackle business challenges from a unique perspective. With a humanistic approach and the ability to design effective technological solutions that drive business success.
        </p>
      </div>
      <div class="techContainer">
        <h1>Languages and Tools</h1>
        <div class="technology-section">
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
      </div>

      <div class="buttonContainer">
        <h1>Also see</h1>
        <div class="buttonSub">
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
  </div>
</div>
</template>

<script setup></script>

<style scoped>
.logo-img {
  height: auto;
  width: 40px;
}
.wrapper{
  display: flex;
  justify-content: center;
}
.main-container {
  display: flex;
  background-color: rgb(38, 21, 83);
  margin: 5%;
  border-radius: 20px;
  width: 75%;
  /* box-shadow: 5px 5px 10px rgba(255, 255, 255, 0.3); */

  /* flex-direction: column; */
  /* align-items: center; */
}
.container1 {
  background-color: #e8ebf8;
  width: 20%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px 10px 20px 10px;
  flex-direction: column;
  margin: 15px 0 15px 15px;
  border-radius: 20px;
  box-shadow: 5px 5px 10px rgba(255, 255, 255, 0.3);

}
.container1 a {
  text-decoration: none;
  color: inherit;
}
.container2 {
  display: flex;
  background-color: #bec7f8;
  color: rgb(0, 0, 0);
  width: 75%;
  flex-direction: column;
  align-items: center;
  padding: 20px 10px 20px 10px;
  justify-content: space-around;
  border-radius: 20px;
  margin: 2rem;
  box-shadow: 5px 5px 10px rgba(255, 255, 255, 0.3);

}

.container2 a {
  text-decoration: none;
  color: inherit;
}

.profile {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.profile img {
  width: 8rem;
  border-radius: 50%;
  /* box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3); */
}

.social-links {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.social-links a {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.about {
  display: flex;
  align-items: center;
  flex-direction: column;
  text-align: left;
  margin-left: 2rem;
  margin-right: 2rem;
}

.about p {
  display: flex;
  flex-direction: column;
  align-items: center;
  /* background-color: #d3d9f5; */
  /* border-radius: 20px; */
  padding: 10px;
  /* box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3); */
}

.buttonContainer {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.buttonSub {
  display: flex;
  flex-direction: row;
  color: black;
}
.button {
  border-radius: 20px;
  margin: 10px;
  padding-left: 5px;
  padding-right: 5px;
  background-color: #d3d9f5;
  box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3);
}

.techContainer {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.technology-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  /* background-color: #d3d9f5; */
  /* border-radius: 20px; */
  padding: 5px;
  /* box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3); */
}

@media only screen and (max-width: 900px) {
  .main-container{
    width: 95%;
  }
}
</style>
