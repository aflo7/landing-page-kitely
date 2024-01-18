<script setup></script>

<template>
  <div class="nav-wrapper">
    <nav>
      <h1>KitelyTech</h1>
      <div class="right-icon"></div>
      <div class="right-nav-wrapper">
        <div>Solutions</div>
        <div>Capabilities</div>
        <div>Company</div>
        <button class="get-in-touch-btn">Get in Touch</button>
      </div>
    </nav>
  </div>

  <div class="main-wrapper">
    <main>
      <div style="padding: 80px 20px" class="left-main">
        <h2>Web App Development</h2>
        <p class="elevate-text">Elevate Businesses with Custom Web Applications</p>
        <button class="view-capacities-button">View Capacities</button>
      </div>
      <div class="image-wrapper"></div>
    </main>
  </div>
</template>

<style scoped>
.image-wrapper {
  height: 400px;
  background: linear-gradient(rgba(0, 0, 0, 1), rgba(0, 0, 0, 0)),
  url(https://assets-global.website-files.com/651350b7300b08a541ba70ae/65145344e1df33c391ef36c0_african-american-coder-employee-programming-busine-2021-12-09-02-41-56-utc-p-800.jpg);
  background-position: center;
  background-size: cover;
}

.view-capacities-button {
  background-color: transparent;
  border: 1px solid white;
  color: white;
  padding: 10px 20px;
  border-radius: 1000px;
  cursor: pointer;

}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px;
  border-bottom: 1px solid rgb(110, 110, 110);
}

h1,
h2 {
  margin: 0;
}

.right-icon {
  border-top: 3px solid white;
  height: 15px;
  width: 30px;
  border-bottom: 3px solid white;
}

.right-nav-wrapper {
  display: none;
}

h2 {
  font-weight: bold;
  font-size: 3rem;
}

.elevate-text {
  color: lightgray;
}

.left-main {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

</style>
