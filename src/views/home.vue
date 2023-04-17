<template>
    <!--banner image-->
  
    <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
      <div  class="images">
        <div class="profile">
        <img src="../assets/khalil.png" class="rounded-circle"
             height="350px" width="500px">
      </div>
      <div class="content text-center">
        <h1>Muhamamd Khalil Gibran</h1>
        <h3>12150113926</h3>
        <h4>Saya Merupakan Mahasiswa Aktif</h4>
        <h5>Universitas Islam Negeri Sultan Syarif Kasim Riau</h5>
        <h2>Selamat Datang</h2>
      </div>
      <div class="background">
      </div>
      </div>
    </div>
  
  
</template>
  
<script>
  export default {
    name: 'App',
    components: {
      // HelloWorld
    }
  }
</script>
  
<style>
.text-center{
  margin-top: -10px;
  color: #181818;

}

.images {
  margin-top: -90px;
}

.profile {
  padding-top: 20px;
}

#app{
  background: linear-gradient(rgba(3, 29, 86, 0.96), rgba(60, 125, 190, 0.9), rgba(218, 224, 224, 0.96)),center/cover no-repeat;
}


</style>
  