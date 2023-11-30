<template>
  <header class="main-header">
    <div class="container">
      <div class="main-header-wrapper">
        <div class="main-header-content">
          <h1 class="main-header-title">Автомастерская e-queo</h1>
          <p class="main-header-subtitle">Ремонт и благополучие вашего автомобиля</p>
          <a class="page-button" href="#">Записаться на прием</a>
        </div>
      </div>
    </div>
  </header>
  <div class="page-block page-block--light">
    <div class="container">
          <p class="page-block-title">Почему именно мы?</p>
      <div class="advantages-container-wrapper">
        <div class="flex-container">
          <div class="advantages-item">
            <img src="./images/icons/repair_icon.png" alt="icon">
            <p class="advantage-title">
              Быстрый и<wbr/>качественный ремонт
            </p>
          </div>
          <div class="advantages-item"><img src="./images/icons/clock_icon.png" alt="icon">
            <p class="advantage-title">
              Ремонт в назначенный<wbr/>срок
            </p>
          </div>
          <div class="advantages-item"> <img src="./images/icons/safe_icon.png" alt="icon">
            <p class="advantage-title">
              Гарантия 3 месяца
            </p>
          </div>
        </div>
        <div class="flex-container">
          <div class="advantages-item">
              <img src="./images/icons/clock_icon-1.png" alt="icon">
              <p class="advantage-title">
                Круглосуточная работамастерской
              </p>
          </div>
          <div class="advantages-item">
              <img src="./images/icons/sofa_icon.png" alt="icon">
              <p class="advantage-title">
                Комфортная зона<wbr/>обслуживания
              </p>
          </div>
          <div class="advantages-item">
              <img src="./images/icons/child_icon.png" alt="icon">
              <p class="advantage-title">
                Детская игровая зона
              </p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="page-block">
    <div class="container">
          <p class="page-block-title">Фотогалерея</p>
      <div class="gallery-wrapper flex-container">
          <img class="gallery-photo" src="./images/gallery/1.png" alt="gallery-img">
          <img class="gallery-photo" src="./images/gallery/2.png" alt="gallery-img">
          <img class="gallery-photo" src="./images/gallery/3.png" alt="gallery-img">
          <img class="gallery-photo" src="./images/gallery/4.png" alt="gallery-img">
          <img class="gallery-photo" src="./images/gallery/5.png" alt="gallery-img">
      </div>
    </div>
  </div>
</template>
------------------------------------------
<script>
export default {
  data() {},
  methods: {}
}
</script>
------------------------------------------
<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
:root {
  --light-color: #f8f3f5ef;
  --dark-color: #251B23;
  --active-tab-color: #7A363A;
  --button-color: #F0AB4C;
}
body {
  color: var(--light-color);
  font-size: 24px;
  font-family: 'Kanit', sans-serif;
  background-color: var(--dark-color);
}
/* ------------- GENERAL ---------------- */
.page-block-title {
  font-size: 48px;
  display: block;
  text-align: center;
  padding-bottom: 80px;
}
.main-header-title,
.main-header-subtitle,
.page-block-title {
  font-family: 'Jura', sans-serif;
}
.page-block {
  padding: 5% 10% 5% 10%;
}
/* --------------- MAIN HEADER ------------------ */
.main-header {
  background-image: url("images/backgrounds/main-background1.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  padding-left: 15%;
}
.main-header-wrapper {
  min-height: 100vh;
  display: grid;
  align-items: center;
}
.main-header-title {
  font-size: 64px;
}
.main-header-subtitle {
  margin-bottom: 50px;
}
.page-button {
  color: var(--dark-color);
  text-transform: uppercase;
  background-color: var(--button-color);
  text-decoration: none;
  font-size: 18px;
  padding: 17px 45px;
  border-radius: 2px;
  font-weight: 700;
}
.page-block--light {
  background-color: var(--light-color);
  color: var(--dark-color);
}
/* ------------- ADVANTAGES BLOCK ---------------- */
.advantages-container-wrapper {
  display: grid;
  grid-gap: 50px;
}

.flex-container {
  display: flex;
  justify-content: space-evenly;
}
/* ----------------- GALLERY ---------------------*/
.gallery-photo {
  aspect-ratio: 1 / 1;
  width: 10%;
  background-size: 10%;
  background-position: center center;
  transition: 1s;
}
.gallery-wrapper {
  background-color: var(--light-color);
  width: 100%;
}
.gallery-photo:hover {
  background-size: 110%;
}
/*---------------ABOUT COMPANY-----------------*/
.top-button {
  color: var(--light-color);
  background-color: var(--dark-color);
  text-decoration: none;
  text-align: center;
  font-size: 15px;
  display: block;
  width: 370px;
  height: 40px;
  padding: 2% 30%;
  border-radius: 2px;
  font-weight: 700;
}
.top-button:focus{
  background-color: #7A363A;
}
.card{
  margin-top: 80px;
  font-size: 17px;
}
.card-body{
  margin: 5%;
}
.form-button{
  padding-left: 25%;
  padding-top: 100px;
}
form textarea {
  vertical-align: top;
}
/*------------------REGISTRATION-------*/
.main-regist {
  background-image: url("images/backgrounds/regist-background.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  padding: 0%;
}

/*----------------FOOTER-------------------*/
</style>
<script setup>
</script>