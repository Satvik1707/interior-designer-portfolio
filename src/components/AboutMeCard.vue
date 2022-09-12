<template>
  <div>
    <div class="container">
      <div class="column-1 lc">
        <div class="profile-col">
          <img id="profile2" src="../assets/me.png" alt="nothing" />
        </div>
      </div>
      <div class="column-1 rc">
        <div class="info">
          <div class="header">
            <p>THE DESIGNER</p>
            <span></span>
          </div>
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
          <span>
            READ MORE
          </span>
          <!-- <img src="../assets/right-arrow.svg" /> -->
        </router-link>
      </button>
    </div>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  font-family: Century Gothic, sans-serif;
}
.container,
.main {
  margin: 3% 10% 0% 5%;
}

.container {
  display: flex;
  flex-wrap: wrap;
}

.column-1 {
  display: flex;
  flex-direction: column;
  flex: 1;
}

.lc {
  align-items: center;
}

.rc {
  justify-content: center;
}

.profile-col {
  position: relative;
  min-height: 400px;
  min-width: 260.25px;
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

.read-more {
  flex-direction: column;
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
  border: 1px solid #945654;
  cursor: pointer;
  transition: transform 0.3s;
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

.card-header {
  display: flex;
  text-transform: uppercase;
  background-size: 24px 24px;
  border-right: 1px solid #b8b8b8;
}

.card-header p {
  font-size: 1.7em;
  font-weight: 700;
  color: #945654;
  padding-left: 20px;
  padding-bottom: 5px;
  padding-top: 5px;
  /* border-left: 25px solid black; */
}

.card-main {
  display: flex;
  flex-direction: row;
  margin-top: 14px;
  margin-bottom: 14px;
  padding: 3px;
}

.card-main .date {
  text-align: end;
  flex: 1;
}

.card-main .column-info {
  display: flex;
  flex: 1;
  flex-direction: column;
  align-items: flex-start;
  padding-left: 10px;
  border-left: 4px solid #b8b8b8;
}

.card-main .column-info .name {
  font-size: 1.2em;
}

.name-weight {
  font-weight: 700;
}

.card-main .column-info ul {
  margin-top: 15px;
  margin-left: 20px;
  text-align: left;
}

.download-cv {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 70px;
  height: 70px;
  text-decoration: none;
  outline: none;
  margin-right: 30px;
  margin-bottom: 30px;
}

.download-cv button {
  width: 70px;
  height: 70px;
  background: url('../assets/pdf.svg');
  background-repeat: no-repeat;
  background-position: center;
  background-size: 70% 80%;
  outline: none;
  border-radius: 40px;
}

@media (max-width: 768.98px) {
}

@media (max-width: 768.98px) {
  .container {
    flex-direction: column;
    justify-content: center;
    margin: 3% 1em 0% 1em;
    margin-top: 40px;
  }

  .main {
    margin: 3% 2em 0% 2em;
  }

  .rc {
    margin: 40px 1em 0% 1em;
  }
}
</style>

<script>
export default {}
</script>
