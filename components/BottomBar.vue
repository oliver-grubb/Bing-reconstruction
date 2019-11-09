<template>
  <div class="container">
    <img class="arrowdown" src="..\assets\Images\arrowsmall.jpg"/>
    <img class="location" src="..\assets\Images\welcometocalifornia.jpg"/>
    <img class="locationarrowleft" src="..\assets\Images\arrowsmall.jpg"/>
    <img class="locationarrowright" src="..\assets\Images\arrowsmall.jpg"/>
    <div class="newslist">
      <img class="arrowleft" src="..\assets\Images\arrowbig.jpg"/>
      <div class="news">
        <p>Storm dislodges ship</p>
        <img class="newsimg" src="..\assets\Images\Storm dislodges ship.jpg" />
      </div>
      <div class="news">
        <p>Lilly shaves her head</p>
        <img class="newsimg" src="..\assets\Images\lilly shaves head.jpg" />
      </div>
      <div class="news">
        <p>Pirates kidnap crew</p>
        <img class="newsimg" src="..\assets\Images\pirates kidnap crew.jpg" />
      </div>
      <div class="news">
        <p>CEO fired</p>
        <img class="newsimg" src="..\assets\Images\CEO fired.jpg" />
      </div>
      <div class="news">
        <p>On this day 2008</p>
        <img class="newsimg" src="..\assets\Images\onthisday2008.jpg" />
      </div>
      <div class="news">
        <p>Stylist found dead</p>
        <img class="newsimg" src="..\assets\Images\stylist dead.jpg" />
      </div>
      <div class="news">
        <p>Famed astrologer dies</p>
        <img class="newsimg" src="..\assets\Images\famed astrologer dies.jpg" />
      </div>
      <div class="news">
        <p>NHS warning</p>
        <img class="newsimg" src="..\assets\Images\nhs warning.jpg" />
      </div>
      <img class="arrowright" src="..\assets\Images\arrowbig.jpg"/>
    </div>
  </div>
</template>

<script>
export default {
  name: "BottomBar"
};
</script>

<style scoped>
.container {
    margin-top: 31%;
}
.news img {
    border-bottom-left-radius: 5px;
        border-bottom-right-radius: 5px;
        width: 185px
}

.news {
  background-color: rgb(26, 26, 26);
  margin-right: 10px;
  padding: 0;
  float: left;
  border-radius: 6px;
}

.newslist p {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  color: white;
  font-size: 13px;
  margin-top: 10px;
  margin-bottom: 10px;
  margin-left: 15px;
  margin-right: 0px;


}
.arrowleft {
    width: 1%;
    height: 1%;
    float: left;
    transform: rotate(180deg);
    margin-top: 3%;
    margin-right: 35px;
}
.arrowright {
    width: 1%;
    height: 1%;
    margin-top: 3%;
    margin-left: 35px;
}
.arrowdown {
    width: 1.2%;
    height: 1.2%;
    transform: rotate(270deg);
    margin-left: 55px;
    margin-bottom: 10px;
    padding: 5px;
    background-color: rgb(26, 26, 26);
    border-radius: 6px;
}
.location {
    width: 9%;
    height: 9%;
    margin-left: 69%;
    margin-bottom: 10px;
    padding: 7px;
    background-color: rgb(26, 26, 26);
    border-radius: 6px;
}
.locationarrowleft {
    width: 1.2%;
    height: 1.2%;
    margin-bottom: 10px;
    padding: 5px;
    background-color: rgb(26, 26, 26);
    border-radius: 6px;
}
.locationarrowright {
    width: 1.2%;
    height: 1.2%;
    transform: rotate(180deg);
    margin-bottom: 10px;
    padding: 5px;
    background-color: rgb(26, 26, 26);
    border-radius: 6px;
}
</style>