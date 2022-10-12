import CCard from '@coreui/vue/src/components/card/CCard'

<template>
  <div class="container">
    <div class="header">
      <p>My Works</p>
      <p></p>
    </div>
    <div>
      <div class="column-1 lc">
        <div class="profile-col">
          <img
            id="profile2"
            src="../assets/s4.png"
            alt="nothing"
            width="400"
            height="300"
          />
        </div>
        <div class="profile-col">
          <img
            id="profile2"
            src="../assets/s2.jpg"
            alt="nothing"
            width="400"
            height="300"
          />
        </div>
        <div class="profile-col">
          <img
            id="profile2"
            src="../assets/s3.jpg"
            alt="nothing"
            width="400"
            height="300"
          />
        </div>
        <div class="profile-col">
          <img
            id="profile2"
            src="../assets/s1.jpg"
            alt="nothing"
            width="400"
            height="300"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

.column-1 {
  display: flex;
  flex-direction: column;
  flex: 1;
}
.lc {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}
.profile-col {
  position: relative;
  min-height: 300px;
  min-width: 400px;
  border: 3px solid #f3c7c6;
  /* padding: 5px 10px 5px 10px; */
}
.container {
  display: flex;
  flex-direction: column;
  padding-bottom: 4em;
}

.header {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 2em 0 2em;
}

.header p:first-child {
  margin-top: 2.5em;
  margin-bottom: 0.5em;
  font-size: 2em;
}
.header p:last-child {
  font-size: 1em;
  font-weight: 300;
}

.right-column .area img {
  margin-right: 10px;
}
</style>

<script></script>
