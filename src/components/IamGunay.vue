import { CCarousel } from '@coreui/vue'

<template>
  <div class="container">
    <div class="hide">
          <p  style="font-weight: bold;font-size: 22px;">Nandini Gulati</p>
          <p>Interior designer</p>
        </div>
    <div class="left-column">
      <div class="left-column-text">
        <p class="main-text" align="center">Nandini Gulati</p>
        <p class="main-text-desc" align="left">INTERIOR DESIGNER</p>
        <div class="bg">
          <img class="d-block w-100" src="../assets/s3.jpg" alt="slide 1" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="css" scoped>
* {
  padding: 0;
  margin: 0;
}

.hide{
  display: none;
}

.bg {
  height: 100vh;
  /* width: 100vh; */
}
@media (max-width: 800px){
 .bg{
height: auto;
 }
 .left-column{
  width: auto;
 }
}

@media (max-width: 400px){
  .bg{
height: auto;
 }
 .left-column{
  width: auto;
  background-color: pink;
 }
 .left-column img{
  display: none;
 }
 .left-column p{
  display: none;
 }
 .hide{
  display: block;
 }
 .container{
  display: block !important;
  text-align: center;
  background: pink;
 }
}
.fade-enter-active,
.fade-leave-active {
  /* transition: all 0.9s ease; */
  overflow: hidden;
  visibility: visible;
  position: absolute;
  width: 100%;
  opacity: 1;
}

.fade-enter,
.fade-leave-to {
  visibility: hidden;
  width: 100%;
  opacity: 0;
}

img {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  color: black;
  font-weight: bold;
  font-size: 18px;
  transition: 0.7s ease;
  border-radius: 0 4px 4px 0;
  text-decoration: none;
  user-select: none;
  /* padding: 10px; */
}

.next {
  right: 0;
}

.prev {
  left: 0;
}

.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.9);
}
.container {
  display: flex;
  /* flex-wrap: wrap; */
  flex-direction: row;
}

.left-column {
  display: flex;
  position: relative;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  flex-grow: 2;
  /* padding: 10em 3em 10em 3em; */
  background-size: 24px 24px;
  border-left: 1px solid black;
  /* margin-left: 200px; */
  border-right: 1px solid black;
}

.left-column-text {
  margin-left: 40px;
}

.left-column .main-text-desc {
  color: #1c1c1c;
  font-size: 1.3em;
  font-family: Century Gothic, sans-serif;
  align-items: center;
  margin-left: 0px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  /* float: left; */
}
.image {
  height: auto;
  width: auto;
}
.left-column .main-text {
  color: #1c1c1c;
  font-size: 4em;
  font-weight: 900;
  font-family: Copperplate, sans-serif;
  line-height: 60px;
  margin: 10px 0 30px 0;
  position: absolute;
  top: 40%;
  left: 50%;
  transform: translate(-50%, -50%);
  /* float: left; */
}

.left-column .main-text-intro {
  font-family: Century Gothic, sans-serif;
  font-size: 2em;
}

.right-column {
  display: flex;
  justify-content: center;
  align-items: center;
  border-left: 1px solid black;
  border-right: 1px solid black;
  flex-grow: 2;
  max-width: 500px;
  margin-right: 3em;
  -webkit-box-shadow: -14px 3px 52px -26px #0000007a;
  -moz-box-shadow: -14px 3px 52px -26px #0000007a;
  box-shadow: -14px 3px 52px -26px #0000007a;
}

.right-column img {
  /* border-top: 1px solid black; */
  /* border-bottom: 1px solid black; */
  max-width: 80%;
  max-height: 80%;
  /* padding: 15%; */
  /* filter: grayscale(100%) ; */
}

@media (max-width: 575.98px) {
  

  .left-column .main-text-desc {
    color: #1c1c1c;
    font-size: 1.3em;
    font-family: Century Gothic, sans-serif;
  }

  .left-column .main-text {
    color: #3c3c3d;
    font-size: 3em;
    font-weight: 900;
    font-family: Century Gothic, sans-serif;
    line-height: 60px;
    margin: 10px 0 30px 0;
  }

  .left-column .main-text-intro {
    font-family: Century Gothic, sans-serif;
    font-size: 1.5em;
  }
}

/* Small devices (landscape phones, less than 768px) */
@media (max-width: 767.98px) {
}

/* // Medium devices (tablets, less than 992px) */
@media (max-width: 991.98px) {
  .main-text-desc{
    margin-top: 50px;
  }
}

/* // Large devices (desktops, less than 1200px) */
@media (max-width: 1265.98px) {
  .right-column {
    display: none;
  }
}
</style>
<script>
export default {}
</script>
