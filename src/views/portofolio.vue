<template>
 <div class="main-container">
  <div class="container-one">
    <div class="profile">
      <img src="../assets/w.png" alt="">
      <h3>Muhammad Khalil Gibran</h3>
      <p>Universitas Islam Negeri Sultan Syarif Kasim Riau</p>
    </div>
    <div class="sosial-links">
      
        <div class="link">
          <a href="https://github.com/KahlilGibran12"><img src="../assets/github.png" alt="" style="width:30px;height:30px;" >
            <h2>GitHub</h2></a>
        </div>
        <div class="link">
          <a href="https://www.instagram.com/mhdkhalilgibran04/"><img src="../assets/instagram.png" alt="" style="width:30px;height:30px;">
            <h2>Instagram</h2></a>
        </div>
        <div class="link">
          <a href="https://t.me/crystalmystik23"><img src="../assets/telegram.png" alt="" style="width:30px;height:30px;">
            <h2>Telegram</h2></a>
        </div>
        <div class="link">
          <a href="http://wa.me/6282274268796"><img src="../assets/whatsapp.png" alt="" style="width:30px;height:30px;">
            <h2>WhatsApp</h2></a>
        </div>
      
    </div>
  </div>
  <div class="container-two">
     <div class="about-me">
      <h1>About Me</h1>
      <p>Nama Saya Muhammad Khalil Gibran Saya Lahir Pada Tanggal 29 Januari 2004 Di Kota Sibolga, Saya Sekarang Tinggal Di Pandan. Dan Saya Mahasiswa Aktif Universitas Islam Negeri Sultan Syarif Kasim Riau</p>
     </div>
    <div class="tecnology-section">
       <h1>Technolgy Studied</h1>
      <div class="logos">
       <img src="../assets/js.png" alt="" style="width:50px;height:50px;">
       <img src="../assets/java.png" alt="" style="width:70px;height:50px;">
       <img src="" alt="">
       </div> 
     </div>
     <div class="button-container">
        <div class="project-button">
          <a href="">My Project</a>
         </div>
         <div>
         <div class="project-button">
          <a href="">My Resume</a>
         </div>
         </div>
       </div>
   </div>
 </div>
</template>
  
<script>

</script>
  
<style scoped>
  img{
    height: 35px;
  }
  .main-container{
    display: flex;
    flex-direction: row;
    background-color: rgb(170, 192, 187);
    border-radius: 25px;
    
  }
  .container-one{
    background: linear-gradient(rgba(3, 29, 86, 0.96), rgba(60, 125, 190, 0.9), rgba(218, 224, 224, 0.96)),center/cover no-repeat;
    padding: 2.5%;
    margin: 2%;
    color: antiquewhite;
    width: 30%;
    border-radius: 25px;
  }

  .profile img{
    background-color: rgb(195, 214, 208) ;
    height: 13rem;
    border-radius: 30%;
  }
  .link a{  
    text-decoration: none;
    color: rgb(67, 67, 67);
    font-size: 10px;
  }
  .link img{
    height: 13rem;
  }
  .container-two{
    background: linear-gradient(rgba(3, 29, 86, 0.96), rgba(60, 125, 190, 0.9), rgba(218, 224, 224, 0.96)),center/cover no-repeat;
    margin: 2.5%;
    margin-left: 2%;
    border-radius: 2%;
    color: antiquewhite;
    width: 70%;
  }
  .about-me{
    text-align: left;
  }
  .logo img{
    height: 4rem;
  }

  .button-container{
    margin-top: 5px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

    
  }

  .project-button{
    background-color: rgb(0, 0, 0) ;
    border-radius: 25%;
    padding: 5px;
    margin: 6px;
  }
  .project-button a{
    text-decoration: none;
    color: rgb(255, 255, 255);
  }

</style>
  