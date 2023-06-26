<template>
  <div>
  <div>我是子组件，我要给父组件传参</div>
  <button @click="changeFather">点击我向父组件传递参数</button>
  </div>
</template>

<script>
export default {

methods: {
    changeFather(){
        this.$emit('changeEvent','1')
        console.log(this.$attrs)
    }
},
}
</script>

<style>

</style>