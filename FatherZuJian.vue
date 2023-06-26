<template>
  <div>
    <ZiZuJian></ZiZuJian>
  </div>
</template>

<script>
import ZiZuJian from './components/ZiZuJian.vue'
export default {
components:{
  ZiZuJian
},
provide(){
  return {
    user:"qwertyuuiop"
  }
}
}
</script>

<style>

</style>