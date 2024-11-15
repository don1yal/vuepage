<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    props:  {
        msg: String
    }    
}
</script>

<style scoped>
.hello {
  font-size: 1.6rem;
  color: #4a4a4a;
  font-weight: 400;
  padding: 1rem 2rem;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
  margin: 0 auto;
  max-width: 600px;
}

h1 {
  font-size: 2rem;
  color: #333;
  margin: 0;
}
</style>