<template>
  <div>
    <div :class="a===1?'red':'bule'" >
    Hello Word！
  </div>
  <button @click="Bian">点我变色</button>
  </div>
</template>

<script>

export default {
 data() {
  return {
    a:1
  }
 },
methods: {
  Bian(){
    if (this.a === 1) {
      this.a++
    }else{
      this.a=1
    }
  }
},
}
</script>

<style scoped>
.red{
  color: red ;
}
.bule{
  color: blue;
}
</style>