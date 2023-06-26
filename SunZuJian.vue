<template>
  <div>
    <div >我是孙组件，我收到数据啦{{this.user}}</div>
  </div>
</template>

<script>
export default {

inject:['user']
}
</script>

<style>

</style>