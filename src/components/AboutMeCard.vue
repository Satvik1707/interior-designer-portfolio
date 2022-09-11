<template>
  <div>
    <div class="container">
      <div class="column-1 rc">
        <div class="info">
          <div class="header">
            <p>THE DESIGNER</p>
            <span></span>
          </div>
          <!-- <div class="column-1 lc">
            <div class="profile-col">
              <img id="profile2" src="../assets/me2.png" alt="nothing" />
            </div>
          </div> -->
          <div class="description">
            I am an interior designer based in Delhi, India. My expertise lies
            in interior space planning, conceptualizing, design development, and
            execution. I believe that design strategy starts with human
            experience. Everything I create is a reflection of what I sense,
            feel, and see in life and my travels around the world. The heart of
            my designs resonate with my innate style of class with color. My
            signature style is a modern aesthetic approach with luxury and
            minimalism.
          </div>
        </div>
      </div>
      <button class="read-more">
        <router-link to="/about">
          READ MORE
          <img src="../assets/right-arrow.svg" />
        </router-link>
      </button>
    </div>
  </div>
  <!-- <div class="att-container">
    <div class="att-first-down-line" />
    <div class="att-second-down-line" />
  </div> -->
</template>

<style lang="css" scoped>
* {
  margin: 0;
  padding: 0;
}
.container img {
  width: 250px;
  height: 300px;
  float: left;
}

.container {
  display: flex;
  flex-direction: column;
  padding: 5%;
}

.container .header {
  font-size: 2em;
  font-family: Century Gothic, sans-serif;
  font-weight: 600;
  align-items: center;
}

.container .description {
  margin-top: 30px;
  font-family: Century Gothic, sans-serif;
  padding: 2px;
  justify-content: center;
}

.container .read-more {
  display: flex;
  justify-content: center;
  align-items: center;
  border: 0;
  background-color: transparent;
  color: #945654;
  width: 140px;
  height: 60px;
  align-self: flex-end;
  margin-top: 20px;
  margin-right: 10px;
  font-size: 1em;
  font-family: Century Gothic, sans-serif;
  border: 1px solid black;
  cursor: pointer;
  transition: transform 0.3s;
}
.column-1 {
  display: flex;
  flex-direction: column;
  flex: 2;
}

.lc {
  align-items: left;
}

.rc {
  justify-content: center;
}

.profile-col {
  position: relative;
  max-height: 10px;
  max-width: 250px;
  border: 3px solid #f3c7c6;
  /* padding: 5px 10px 5px 10px; */
}

.column-1 .header {
  flex: 1;
}

.column-1 .description {
  flex: 1;
  text-align: justify;
}

#profile {
  position: absolute;
  max-height: 400px;
  transform: rotate(0deg);
  -webkit-transition: opacity 0.25s ease-in-out;
  -moz-transition: opacity 0.25s ease-in-out;
  -o-transition: opacity 0.25s ease-in-out;
  transition: opacity 0.25s ease-in-out;
}

#profile:hover {
  opacity: 0;
}

#profile2 {
  position: absolute;
  max-height: 400px;
  transform: rotate(0deg);
}

.header {
  display: flex;
  align-items: center;
  font-size: 1.5em;
  font-weight: 900;
  color: #945654;
  margin-bottom: 30px;
}

.header span {
  width: 40px;
  margin-left: 15px;
  height: 2px;
  background-color: black;
}

.left-container {
  flex: 1;
}
.container .read-more:hover {
  transform: rotate(-10deg);
}

.container .read-more img {
  width: 20px;
  height: 20px;
  margin-left: 8px;
}

.read-more a {
  text-decoration: none;
  outline: none;
  color: #945654;
}

.header {
  align-items: center;
}
</style>

<script>
export default {}
</script>
