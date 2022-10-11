<template>
  <div class='container b-blue'>
    <div class='row'>
      <div class='col'>
        <input type="text" class="form-control" v-model='text'>
      </div>
    </div>
    <div class='row mt-3'>
      <div class="col t-white">
      Good luck typing!!

      </div>
    </div>
    
  </div>  
</template>

<script>
export default {
  data(){
    return {
        text: ""
    }
  },
  mounted(){
  },
  updated(){
  },
  methods:{
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import "../styles/variable.scss";
  .b-blue{
    background-color: $bg-test;
  }
  .t-white{
    color: $color-white;
  }
</style>