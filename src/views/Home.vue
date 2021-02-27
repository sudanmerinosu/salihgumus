<template>
  <div class="home">
    <div class="container">
      <div class="inclusive">
        <div id="upBox" class="box">
          <img src="../assets/images/header.jpg" alt="" />
        </div>
        <div id="downBox" class="box">
          <div>
            <div class="text">
              <p><b>Salih </b>Gümüş</p>
              <span>Developer</span>
            </div>
          </div>
        </div>
        <div id="downSection">
          <h1>Selam</h1>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus itaque obcaecati
            eveniet illo nisi repellat omnis amet consequuntur libero earum consequatur voluptates
            suscipit odio laboriosam, quod aliquid deleniti voluptatem ex
          </p>
        </div>
        <div id="infoSection">
          <div class="address">Adana/Türkiye</div>
          <div id="iconSection">
            <div class="uk-column-1-2">
              <div>
                <a href="https://www.instagram.com/sudanmerinosu/">
                  <i class="im im-instagram" />
                </a>
              </div>
              <div>
                <a href="https://www.linkedin.com/in/salihgumus/">
                  <i class="im im-linkedin" />
                </a>
              </div>
            </div>
            <div class="uk-column-1-2">
              <div>
                <a href="https://twitter.com/sudanmerinosu">
                  <i class="im im-twitter" />
                </a>
              </div>
              <div>
                <a href="">
                  <i class="im im-blogger" />
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.inclusive {
  width: 600px;
  position: relative;
  margin-top: 40px;
  margin-bottom: 30px;
  height: 870px;
  margin-right: auto;
  margin-left: auto;
  background-color: white !important;
  -webkit-box-shadow: 0px 0px 50px -15px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 0px 0px 50px -15px rgba(0, 0, 0, 0.75);
  box-shadow: 0px 0px 50px -15px rgba(0, 0, 0, 0.75);
}
#upBox {
  margin-left: 200px;
  z-index: 1;
}
#downBox {
  background-color: #e8e8e8;
  margin-top: 200px;
  margin-left: 100px;
}
#downSection {
  background-color: white;
  position: absolute;
  bottom: 175px;
  margin-left: 25px;
  letter-spacing: 3px;
  line-height: 20px;
}
#infoSection {
  padding-top: 700px;
  letter-spacing: 3px;
  line-height: 20px;
  text-align: center;
}
#infoSection a {
  color: black;
}
#downSection p {
  font-size: 12px;
}
#iconSection {
  padding-top: 20px;
}

.box {
  width: 300px;
  height: 300px;
  position: absolute;
  margin-top: 100px;
}

.text {
  font-family: Oswald;
  position: absolute;
  bottom: 20px;
  margin-left: 25px;
  letter-spacing: 5px;
  line-height: 15px;
}
.text p {
  font-size: 18px;
}

i {
  margin: 10px;
}
</style>
