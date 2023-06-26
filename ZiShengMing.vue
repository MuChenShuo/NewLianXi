<template>
  <div></div>
</template>

<script>
export default {
beforeCreate() {
  console.log('我是子组件',"beforeCreate");
},
created() {
  console.log('我是子组件',"created");
},
beforeMount() {
  console.log('我是子组件',"beforeMount");
},
mounted() {
  console.log('我是子组件',"mounted");
},
beforeDestroy() {
   console.log('我是子组件',"beforeDestroy");
},
destroyed() {
  console.log('我是子组件',"destroyed");
},
}
</script>

<style>

</style>