<template>
  <div id="app">
    <listing_table/>

  </div>
</template>

<script>
import listing_table from './components/listing_page/table.vue'


export default{
  name:'app',
  components:{
    listing_table
  }  
}



</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
