<template>
  <div class="container-fluid m-0 p-0">
    <div id="cover" class="full-height  .bg-danger.bg-gradient p-4">
      <div class="col-lg-12 pt-4 my-auto">
            <img id="cover-img" src="../assets/bg_primary_001.jpg" class="img-fluid">
      </div>    
    </div>

    <div id="page01" class="bg-danger p-4">
      <div class="col-lg-12 pt-4 my-auto">
        <img id="cover-img" src="../assets/bg_primary_002.jpg" class="img-fluid">
      </div>
    </div>

    <div id="page02" class="bg-warning p-4">
      <div class="col-lg-12 pt-4 my-auto">
        <img id="cover-img" src="../assets/bg_primary_003.jpg" class="img-fluid">
      </div>
    </div>
    

    <div id="page03" class="bg-primary p-4">
      <div class="col-lg-12 pt-4 my-auto">
        <img id="cover-img" src="../assets/bg_primary_004.jpg" class="img-fluid">
      </div>
    </div>

    <div>creado con ❤️ por <b>Primaria Barrio Pedregal</b></div>

  </div>

  
</template>

<script>
export default {
  
  data () {
    return{
      title: 'Travel Treasury'
    }
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #cover{
    background-color: #92D2F2;
    background: url('../assets/bg_mt.jpg') no-repeat center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }

  

  

</style>