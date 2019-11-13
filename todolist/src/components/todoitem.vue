
<template>
  
  <li @click="change">{{content}}</li>
  
  
  
</template>
  
<script>
export default {
  props:['content','index'],
  methods:{
    change:function(){
    this.$emit('delete',this.index)
    }
  }
}
</script>
<style>

</style>
