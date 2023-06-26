<template>
  <div>
    <div id="app">
      <!-- <button @click="arr.push(Math.random() * 10)">添加一个数字</button>
      计算和：{{ getSum }} -->
       <input type="text" v-model="val">
        <p>{{rever}}</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      arr: [1, 2, 3, 4, 5],
      val:"",
    }
  },
  computed: {
    // getSum() {
    //   var sum = 0;
    //   this.arr.forEach((i) => {
    //     sum += i;
    //   });
    //   return sum;
    // },
    rever(){
      return this.val.split('').reverse().join('')
    }
  },
};
</script>

<style>
</style>