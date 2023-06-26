<template>
  <div>
   <ChildRen :data="data" :array="array" :object="object" ></ChildRen>
  </div>
</template>

<script>
import ChildRen from './components/ChildRen.vue'
export default {
components:{ChildRen},
data() {
  return {
    data:'hello word !',
    array:[1,2,3,4,5]  ,
    object:{
       title1:"1",
       title2:"2",
       title3:"3"
    }
    }
},}
</script>

<style scoped>

</style>