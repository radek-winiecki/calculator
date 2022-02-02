<template>
  <div class="calculator">
    <div class="display">hello</div>
    <div>C</div>
    <div>+/-</div>
    <div>%</div>
    <div>÷</div>
    <div>hello</div>
    <div>hello</div>
  </div>
</template>

<script>
export default {
 
}
</script>

<style scoped>

.calculator {
  font-size: 40px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}

.display {
  grid-column: 1/5;
  background-color: red;
}

</style>
