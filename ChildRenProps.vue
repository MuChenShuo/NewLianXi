<template>
  <div>
   <div class="root">
    {{data}}
    {{array[0]}}
    {{object.title1}}
   </div>
  </div>
</template>

<script>
export default {
// props:{
//     data:{
//         type:String,
//         default:"wu-zhi"
//     },
//     array:{
//         type:Array
//     },
//     object:{
//         type:Object
//     }
// }

props:['data','object','array']

}
</script>

<style>

</style>