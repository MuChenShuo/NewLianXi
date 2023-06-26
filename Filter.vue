<template>
  <div>
  
    <button @click="guolv">点我开始过滤</button>
    <button @click="quchong">点我开始去重</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      shuju:[1,1,2,2,3,3,4,4,5,5],
      xin:'', 
    }
  },
methods: {
  guolv(){
    this.xin = this.shuju.filter(function (val) {
      return val > 2
    })
    console.log(this.xin);
  },
  quchong(){
    this.xin = this.shuju.filter(function (number,index,arr) {
      return arr.indexOf(number) == index 
    })
    console.log(this.xin);
  }
},
}
</script>

<style scoped>
.a{
  width: 100px;
  height: 30px;
  border: 1px solid black;
}
</style>