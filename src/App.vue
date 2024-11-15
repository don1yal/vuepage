<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />
    <div class="wrapper">
      <HelloWorld msg="Hello World! This my beautiful component." />
    </div>
  </header>
</template>

<style scoped>
.app {
  font-family: 'Helvetica', 'Arial', sans-serif;
  color: #333;
  background-color: #f9f9f9;
  text-align: center;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

header {
  padding: 2rem;
}

.logo {
  margin-bottom: 2rem;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.wrapper {
  margin-top: 2rem;
  max-width: 800px;
  margin: 0 auto;
}
@media (min-width: 1024px) {
  header {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
  }
}
</style>
