
<template>
  <div>
     <el-checkbox v-model="checked1" >备选项1</el-checkbox>
<el-checkbox v-model="checked2" >备选项2</el-checkbox>
  </div>
</template>

<script>
export default {
 data() {
   return {
   
     checked1: false,
     checked2: true,

   }
 },
};
</script>

<style scoped>

</style>
  
  