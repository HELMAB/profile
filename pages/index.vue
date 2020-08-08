<template>
  <div class="mab-container">
    <div class="mab-sidebar">
      <div class="mab-menu">
        <h3>
          <i class="fa fa-home"></i>
        </h3>
      </div>
      <div class="mab-social text-center">
        <div><i class="fa fa-facebook-official"></i></div>
        <div><i class="fa fa-github"></i></div>
        <div><i class="fa fa-twitter"></i></div>
      </div>
    </div>
    <div class="mab-main">
      <div class="mab-navbar">

      </div>
      <div class="mab-content"
           style="background-image: url(/img/me.png)">
        <h1>Mab</h1>
        <p>A Designer/Frontend Developer With a<br/>Passion for Web Design, Base in Phnom Penh, Cambodia</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
@import "./../node_modules/font-awesome/css/font-awesome.min.css";
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@700&display=swap');

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.text-center {
  text-align: center;
}

.mab-container {
  width: 100%;
  height: 100vh;
  background: #000;
  display: flex;
  grid-template-columns: 80px 1fr;
  font-family: "Nunito", sans-serif;
  color: white;
}

.mab-sidebar {
  width: 80px;
  background: #0e0e0e;
  height: 100vh;
  position: relative;
  text-align: center;
}

.mab-menu {
}

.mab-social {
  position: absolute;
  bottom: 0;
  width: 100%;
}

.mab-social i {
  padding: 5px;
  border: 1px solid #ddd;
  margin-bottom: 15px;
  border-radius: 50%;
  cursor: pointer;
  width: 30px;
  height: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.mab-social div {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.mab-main {
  width: 100%;
  height: 100vh;
}

.mab-content {
  padding: 300px;
  height: 100vh;
  width: 100%;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
