<template>
  <div class="container">
    <h1 class="glow-text">Si tu veux tu peux, l'impossible n'est pas toi</h1>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #000;
}

.glow-text {
  font-size: 3em;
  color: #fff;
  text-align: center;
  animation: glow 1s infinite alternate;
}

@keyframes glow {
  from {
    text-shadow: 0 0 10px #fff, 0 0 20px #ff00ff, 0 0 30px #ff00ff, 0 0 40px #ff00ff, 0 0 50px #ff00ff, 0 0 60px #ff00ff, 0 0 70px #ff00ff;
  }
  to {
    text-shadow: 0 0 20px #fff, 0 0 30px #ff00ff, 0 0 40px #ff00ff, 0 0 50px #ff00ff, 0 0 60px #ff00ff, 0 0 70px #ff00ff, 0 0 80px #ff00ff;
  }
}
</style>
