<template>
  <div class="grid-container">
    <div class="section1"></div>
    <div class="section2"></div>
    <div class="section3">
      <div class="sub-section1"></div>
      <div class="titular"><p class="p-titular">Visa to</p></div>
      <div><p class="p-titular">the moon</p></div>
    </div>  
    <div class="section4">
      <div class="sub-section2">
        <div class="irocket"></div>
        <div></div>
        <div class="irocket-p"><p class="p-irocket">Your trip start here</p></div>
        <div></div>
        <div class="irocket-barra"></div>
        <div></div>
        <div class="irockethastag"><p class="p-hastag">#moontrip #visamoon #moontickets</p></div>
      </div>
      <div class="sub-section3">
        <div></div>
        <div class="slider">
          <div class="barras">
            <hr class="verde">
            <hr class="blanco">
            <hr class="blanco">
          </div>
          <div class="botones">
            <button class="boton">prev</button>
            <a href="#">view ease</a>
            <button class="boton">next</button>
          </div>
        </div>
      </div>
      <div class="sub-section4">
        <div class="rocket"></div>
      </div>
    </div>
  </div>
</template>

<style>

body{
  width: 100vw;
  height: 100vh;
  background-color: #1f5556;
}

.p-titular{
  font-family: 'Montserrat', sans-serif;
  font-size: 5vw;
  font-weight: 700;
  padding-left: 25.5vw;
}

.p-irocket{
  font-family: 'Merriweather', serif;
  font-size: 1.5vw;
  font-weight: 500;
  letter-spacing: 0.08vw;
}

.p-hastag{
  font-family: 'Merriweather', serif;
  font-style: italic;
}

button{
  border: none;  
}

.grid-container {
  display: grid;
  grid-template-columns: 31vw 58vw;
  grid-template-rows: 2vh 85.5vh;
}

.section3{
  z-index: 1;
  background-image: url("../assets/images/rock.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position-y: top;
  background-position-x: right;
  display: grid;
  grid-template-columns: 51vw;
  grid-template-rows: 35vh 15vh 7vh;
}

.section4{
  background-image: url("../assets/images/background.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: bottom;
  display: grid;
  grid-template-columns: 20vw 18vw 31vw;
}

.sub-section1{
  background-image: url("../assets/images/logo.png");
  background-repeat: no-repeat;
  background-position-x: 16vw;
  background-position-y: 8vh;
}

.sub-section2{
  display: grid;
  grid-template-rows: 20vh 0.3vh 4vh 0.3vh 0.7vh 1vh 3vh;
  grid-template-columns: 17vw;
}

.sub-section3{
  display: grid;
  grid-template-rows: 60vh 33vh
}

.sub-section4{
  display: grid;
  grid-template-rows: 60vh
}

.titular{
  padding-top: 6.5vh;
}

.rocket{
  background-image: url("../assets/images/rocket.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}

.slider{
  background-color: #252839;
  display: grid;
  grid-template-rows: 23vh 10vh;
}

.irocket{
  background-image: url("../assets/images/icon_rocket.png");
  background-repeat: no-repeat;
  background-position-x: 3vw;
  background-position-y: bottom;
}

.irocket-p{
 padding-left: 3vw;
}

.irocket-barra{
  background-image: url("../assets/images/icon_rocket.png");
  background-repeat: no-repeat;
  background-position-x: 3vw;
  background-position-y: bottom;
}

.irockethastag{
  padding-left: 3vw;
}

.botones{
  display: flex;
  justify-content: center;
  align-items: center;
}

.barras{
  display: flex;
  justify-content: center;
  padding-top: 8vh;
}

.boton{
  background-color: #252839;
  color: #1ba48b;
  font-size: 1.5vw;
  margin: 0.7vw;
  cursor: pointer;
  font-family: 'Merriweather', serif;
}

a{
  color: white;
  text-underline-offset: 1vh;
  font-size: 1.5vw;
  margin: 0.7vw;
  cursor: pointer;
  font-family: 'Merriweather', serif;
}

.verde{
  height: 0.1vw;
  width: 25%;
  background-color: #1ba48b;
}

.blanco{
  height: 0.1vw;
  width: 25%;
  background-color: white;
}

@media only screen and (max-width:360px) {

  body{
    background-image: url("../assets/images/background.jpg");
    background-position-y: 65vh;
  }

  .grid-container {
    display: grid;
    grid-template-columns: 100vw;
    grid-template-rows: 0vh 0vh 20vh 45vh;
  }

  .section3{
    display: grid;
    grid-template-columns: 100vw;
    grid-template-rows: 37vh 16vh 7vh;
  }

  .sub-section1{
    background-position-x: 26vw;
    background-position-y: 4vh;
  }

  .sub-section2{
    display: grid;
    grid-template-rows: 80vh 0.3vh 4vh 3vh 0.8vh 1vh 58vh;
    grid-template-columns: 100vw;
    background-image: url("../assets/images/rocket.png");
    background-size: cover;
    background-repeat: no-repeat;
    background-position-x: top;
  }

  .sub-section3{
    display: none;
  }

  .sub-section4{
    display: grid;
    grid-template-rows: 0vh;
    grid-template-columns: 0vw;
  }

  .section4{
    display: grid;
    grid-template-rows: 45vh;
    grid-template-columns: 100vw;
  }


  .p-titular{
    font-family: 'Montserrat', sans-serif;
    font-size: 14vw;
    font-weight: 700;
    padding-left: 14vw;
  }

  .titular{
    padding-top: 9vh;
  }

  .p-irocket{
    font-family: 'Merriweather', serif;
    font-size: 10vw;
    font-weight: 600;
    letter-spacing: 0.08vw;
  }

  .p-hastag{
    font-family: 'Merriweather', serif;
    font-style: italic;
    font-size: 8vw;
  }
}

</style>