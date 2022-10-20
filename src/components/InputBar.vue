<template>
  <div id="inputBar">
    <div class="row justify-content-center">
      <div class="col-6 text-center">
        <input type="text" class="w-100">
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
</style>