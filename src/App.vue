<template>
  <div class="navbar">
    <div class="navbar-main">
      <h1>Главная</h1>
      <h1>Донат</h1>
      <h1>Карта мира</h1>
      <h1>Правила</h1>
      <h1>Дискорд</h1>
      <h1>Online - 5/100</h1>
    </div>
  </div>

  <div class="about-div">
    <div class="about-text">
      <h1 style="margin-bottom: 30px">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, omnis?
        Vel eaque dicta quia rem incidunt eligendi expedita magni. Ut incidunt
        et facere expedita necessitatibus alias error sunt quos quod.
      </h1>
      <h1>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem,
        hic. Ex ducimus, enim molestias, perspiciatis quasi debitis a repellat
        error sint pariatur suscipit quidem vel! Est nobis quos atque
        voluptatibus facere earum officia, et libero.
      </h1>
    </div>
    <img class="about-img" src="./KI05k1kcjKg.jpg" alt="" />
  </div>

  <div class="questions-div">
    <h1 class="questions-title">Часто задаваемые вопросы:</h1>
    <div class="questions-blocks">
      <div class="question">
        <h1 class="question-title">Aboba</h1>
        <h2 class="question-description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis
          iste soluta, magnam similique voluptatum ratione!
        </h2>
      </div>
      <div class="question">
        <h1 class="question-title">Aboba</h1>
        <h2 class="question-description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis
          iste soluta, magnam similique voluptatum ratione!
        </h2>
      </div>
      <div class="question">
        <h1 class="question-title">Aboba</h1>
        <h2 class="question-description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis
          iste soluta, magnam similique voluptatum ratione!
        </h2>
      </div>
    </div>
  </div>

  <div class="screenshots-main">
    <h1 class="screenshots-title">А вот и скриншоты карты нашего сервера:</h1>
    <div class="screenshots-div">
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
      <img src="./screen.png" alt="" class="screenshot" />
    </div>
  </div>

  <div class="pass-main">
    <h1 class="pass-title">Как купить проходку?</h1>
    <h1 style="display: flex; flex-direction: column">
      <span>Нажми на кнопку ниже и заполни форму!</span>
      <span>Проходку купило уже % человек!</span>
    </h1>

    <button class="buy-button">
      <h1>Купить походку 190 <s>260</s></h1>
    </button>
  </div>
  <hr style="width: 70%; margin-left: auto; margin-right: auto" />
  <footer>
    <h1>Copyright LimeProject, 2022</h1>
    <h1>Вся информация на сайте не является публичной офретой</h1>
  </footer>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter&family=Montserrat:wght@200;600&display=swap");
* {
  margin: 0px;
  padding: 0px;
  font-family: "Montserrat", sans-serif;
  color: #dfdfdf;
}

*::-webkit-scrollbar {
  width: 7px;
  height: 7px;
}
*::-webkit-scrollbar-track-piece {
  background-color: #36393e;
}
*::-webkit-scrollbar-thumb {
  height: 50px;
  background-color: #202225;
  border-radius: 4px;
}

body {
  background: #36393e;
  height: 12000px;
}

footer {
  margin-left: auto;
  margin-right: auto;
  margin-top: 50px;
  width: 1130px
}

footer > h1 {
  margin-left: auto;
  margin-right: auto;
}

.navbar {
  height: 80px;
  color: #dfdfdf;
  box-shadow: 0 0 10px black;
}
.navbar-main {
  width: 1200px;
  height: 100%;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.about-div {
  /* background: steelblue; */
  width: 1100px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 50px;
  margin-bottom: 50px;
  color: #dfdfdf;
  display: flex;
  padding: 15px;
  border-radius: 10px;
  border: 3px #dfdfdf solid;
}

.about-text {
  margin-top: auto;
  margin-bottom: auto;
}

.about-img {
  width: 400px;
}

.questions-div {
  width: 1130px;
  margin-left: auto;
  margin-right: auto;
}

.questions-title {
  text-align: center;
  font-size: 45px;
}

.questions-blocks {
  margin-top: 50px;
  display: flex;
  justify-content: space-between;
}

.question {
  border-radius: 10px;
  padding: 10px;
  border: 3px #dfdfdf solid;
  width: 335px;
}

.question-title {
  text-align: center;
  margin: 5px 0px 5px 0px;
}

.screenshots-main {
  margin: 50px 0px 50px 0px;
  width: 1130px;
  margin-left: auto;
  margin-right: auto;
}

.screenshots-title {
  text-align: center;
  font-size: 45px;
  margin-bottom: 35px;
}

.screenshots-div {
  /* background: steelblue; */
  height: 300px;
  width: 1130px;
  overflow-x: auto;
  display: flex;
  padding: 15px;
}

.screenshot {
  /* width: 100px; */
  height: 100%;
  margin-right: 50px;
  background: tan;
}

.pass-main {
  width: 1130px;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 50px;
}

.pass-title {
  text-align: center;
  font-size: 45px;
  margin-bottom: 20px;
}

/* .costil-h1 {
  display: flex;
  flex-direction:column;
} */

.buy-button {
  margin-top: 50px;
  margin-left: 315px;
  margin-right: 315px;
  font-weight: 700;
  padding: 15px 2px 15px 2px;
  width: 500px;
  border: none;
  border-radius: 4px;
  background-color: #1d72f2;
  color: white;
  font-size: 15px;
  line-height: 25px;
}
.buy-button:hover {
  background-color: #0b5ed7;
  border-color: #0a58ca;
  cursor: pointer;
}
</style>
