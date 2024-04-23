<template>
  <div class="wrapper">
    <div class="main-container">
      <div class="container1">
        <div class="profile">
          <img src="../assets/profilepic.png" alt="" />
          <h3>Trần Trường Giang</h3>
          <p>Sofware Engineer</p>
        </div>
        <div class="cocial-link">
          <div class="link">
            <a href="https://github.com/trggiang0704">
              <img src="../assets/github.png" alt="" />
              <h2>GitHub</h2></a
            >
          </div>
          <div class="link">
            <a href="https://www.facebook.com/Giangtit1004/">
              <img src="../assets/facebook.png" alt="" />
              <h2>Facebook</h2></a
            >
          </div>
          <div class="link">
            <a href="https://www.instagram.com/trgg_giang/">
              <img src="../assets/instagram.png" alt="" />
              <h2>Instagram</h2></a
            >
          </div>
          <div class="link">
            <a href="mailto:trggiang107@gmail.com">
              <img src="../assets/email.png" alt="" />
              <h2>Gmail</h2></a
            >
          </div>
        </div>
      </div>
      <div class="container2">
        <div class="about-me">
          <h1>About Me</h1>
          <p>Date of birth: 10/07/2004</p>
          <p>Tel: 0866100704</p>
          <p>Email: Trggiang107@gmail.com</p>
          <p>Degree: Computer Science Engineer</p>
          <p>GPA: 3.6/4</p>
          <p>Toeic: 750/990</p>
          <p>jLPT: N4+</p>
        </div>
        <div class="technology-section">
          <h1>Technologies Studied</h1>
          <div class="logos">
            <img src="../assets/c++.png" alt="" />
            <img src="../assets/c.png" alt="" />
            <img src="../assets/css.png" alt="" />
            <img src="../assets/html-5.png" alt="" />
            <img src="../assets/js.png" alt="" />
            <img src="../assets/python.png" alt="" />
          </div>
        </div>
        <div class="button-container">
          <div class="project-button">
            <a href="">My project</a>
            <div class="arrow-down"></div>
          </div>
          <div class="project-button">
            <a
              href="https://scontent.fhan5-10.fna.fbcdn.net/v/t1.15752-9/437278109_321694530711051_40806014862253106_n.png?_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHyGln8mc3HOIV7YXsfY0GwMSqHJHArXFAxKockcCtcUC7Z4GnL9ksysYIT7iwt1fUnMN2GIocp3Pzf_qxZ6Czy&_nc_ohc=sxSI6ujJTUAAb5RMqWc&_nc_ht=scontent.fhan5-10.fna&oh=03_Q7cD1QFxxAa1D2TBISVqj3EsQyf0fS-s5lt7car7FnWABaZfkQ&oe=664F15FB"
              >My Resume</a
            >
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
.arrow-down {
  margin-left: 35px;
  width: 0;
  height: 0;
  border-left: 10px solid transparent;
  border-right: 10px solid transparent;
  border-top: 15px solid black;
}
.wrapper {
  display: flex;
  justify-content: center;
}
img {
  height: 40px;
}
.main-container {
  display: flex;
  flex-direction: row;
  background-color: #fce0ef;
  border-radius: 25px;
  width: 60%;
}
.container1 {
  background-color: #d8baec;
  padding: 2.5%;
  width: 30%;
  border-radius: 25px;
}
.link a {
  text-decoration: none;
  color: #2c3e50;
  font-size: 15px;
}
link img {
  height: 2rem;
}
.container2 {
  width: 70%;
  font-size: 20px;
  margin: 2%;
}
.profile img {
  height: 6rem;
  border-radius: 50%;
}
.about-me {
  text-align: left;
  margin-left: 10px;
}
.logos img {
  height: 2.5rem;
}
.button-container {
  margin-top: 10%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.project-button {
  background-color: #ffafbc;
  border-radius: 15px;
  padding: 5px;
  margin: 5px;
}
.project-button a {
  text-decoration: none;
  color: #fff;
}
@media only screen and (max-width: 950px) {
  .main-container {
    width: 95%;
  }
}
</style>