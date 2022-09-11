<template>
  <div class="header">
    <div class="line"></div>
    <p>GET IN TOUCH</p>
    <div class="line"></div>
  </div>
  <div class="container">
    <div class="info">
      <div class="info-information">
        <div class="info-address">
          <p>Office</p>
          <p>
            64,<br />Dyal Singh Colony<br />
            Karnal, India -132001
          </p>
        </div>
        <div class="info-social">
          <div class="email">
            <p>General email:</p>
            <p>nandinigulati2001@gmail.com</p>
          </div>
          <div class="call-us">
            <p>Call me</p>
            <p>+91 9729543566(IN)</p>
          </div>
        </div>
      </div>
    </div>
    <div class="contact">
      <div class="att-1" />
      <ul>
        <li>
          <a href="https://www.linkedin.com/in/nandini-gulati-246744246/">
            <img src="../assets/linkedin.svg" width="24" height="24" />
          </a>
        </li>
        <li>
          <a href="https://www.behance.net/nandini_gulati">
            <img src="../assets/behance-logo.svg" width="24" height="24" />
          </a>
        </li>
        <li>
          <a href="mailto:nandinigulati2001@gmail.com">
            <img src="../assets/gmail-logo.svg" width="24" height="24" />
          </a>
        </li>
        <!-- <li>
          <a href="https://www.instagram.com//">
            <img src="../assets/instagram.svg" width="24" height="24" />
          </a>
        </li> -->
        <li>
          <a href="tel:+91 9729543566">
            <img src="../assets/phone.svg" width="24" height="24" />
          </a>
        </li>
      </ul>
      <div class="att-1" />
    </div>
  </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

.header {
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: center;
  margin-top: 3em;
}

.header p {
  font-size: 2em;
  padding-left: 3%;
  padding-right: 3%;
  text-align: center;
  white-space: nowrap;
}

.header .line {
  width: 100%;
  height: 1px;
  right: 0;
  background-color: #945654;
}

.container {
  display: flex;
  flex-wrap: wrap;
  padding: 5%;
  padding-left: 10%;
}

.container .info {
  display: flex;
  flex-direction: column;
  flex-grow: 2;
  max-width: 70%;
}

.container .contact {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  min-width: 30%;
}
.info-text {
  padding-bottom: 3vw;
  font-size: 1.5em;
  font-family: Century Gothic, sans-serif;
  max-width: 90%;
}

.info-information {
  display: flex;
  flex-wrap: wrap;
  min-width: 20%;
}

.info-address {
  flex-grow: 1;
}

.info-address p:first-child {
  font-size: 0.8em;
  color: gray;
}

.info-address p:last-child {
  line-height: 2;
}

.info-social {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

.email {
  flex: 1;
}

.email p:first-child {
  font-size: 0.8em;
  color: gray;
}

.call-us {
  margin-top: 10px;
  flex: 1;
}

.call-us p:first-child {
  font-size: 0.8em;
  color: gray;
}

.contact {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: -4%;
}

.contact ul {
  list-style: none;
  margin-top: 15px;
  margin-bottom: 10px;
}

.contact .att-1 {
  width: 1px;
  height: 35%;
  background-color: #945654;
}

@media (max-width: 575.98px) {
  .container {
    padding-bottom: 13%;
  }
}
</style>

<script>
export default {}
</script>
