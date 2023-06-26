<template>
  <div>
    <div>{{Data}}</div>
    <EmitChild @changeEvent="changeData" :shuju="shuju" ></EmitChild>
  </div>
</template>

<script>
import EmitChild from './components/EmitChild.vue'
export default {
components:{
  EmitChild
},
data() {
  return {
    Data:'',
    shuju:"123"
  }
},
methods: {
  changeData(value){
   this.Data = value
  }
},
}
</script>

<style>

</style>