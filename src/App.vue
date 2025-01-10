<template>
  <LandingPage />
</template>

<script>
import LandingPage from './components/views/LandingPage.vue';
export default {
  name: 'App',
  components: {
    LandingPage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  scroll-behavior: smooth;
}
html{
  scroll-behavior: smooth;
}
/* Left Bounce */
@keyframes bounceLeft {
  0%, 20%, 50%, 80%, 100% {
    transform: translateX(0);
  }
  40% {
    transform: translateX(-30px);
  }
  60% {
    transform: translateX(-15px);
  }
}
.bounce-left {
  animation: bounceLeft 2s ease infinite;
}

/* Right Bounce */
@keyframes bounceRightOnce {
  0%, 100% {
    transform: translateX(0);
  }
  50% {
    transform: translateX(30px);
  }
}

.bounce-right-once {
  animation: bounceRightOnce 1s ease-out forwards; 
}

</style>
