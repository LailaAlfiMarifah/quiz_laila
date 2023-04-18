<template>
    <div class="main-container">
     <div class="container-one">
       <div class="profile">
         <img src="../assets/laila.jpg" alt="">
         <h3>Laila Alfi Ma'rifah</h3>
                </div>
       <div class="sosial-links">
         
           <div class="link">
             <a href="https://github.com/LailaAlfiMarifah"><img src="../assets/github.jpg" alt="" style="width:30px;height:30px;" >
               <h2>GitHub</h2></a>
           </div>
           <div class="link">
             <a href="https://www.instagram.com/lalakxyzzz._/"><img src="../assets/instagram.jpg" alt="" style="width:30px;height:30px;">
               <h2>Instagram</h2></a>
           </div>
           <div class="link">
             <a href="https://t.me/lailaalfi9234"><img src="../assets/telegram.jpg" alt="" style="width:30px;height:30px;">
               <h2>Telegram</h2></a>
           </div>
           <div class="link">
             <a href="http://wa.me/6282391427320"><img src="../assets/whatsapp.jpg" alt="" style="width:30px;height:30px;">
               <h2>WhatsApp</h2></a>
           </div>
           <div class="link">
             <a href="mailto:lailaalfimarifah924@gmail.com"><img src="../assets/email.jpg" alt="" style="width:30px;height:30px;">
               <h2>Email</h2></a>
           </div>
         
       </div>
     </div>
     <div class="container-two">
        <div class="about-me">
         <h1><b>About Me</b></h1>
         <p>________________________________________</p>
         <p>Nama                  : Laila Alfi Ma'rifah </p>
         <p>Tempat, tanggal lahir : Ponorogo, 24 September 2003 </p>
         <p>Jenis Kelamin         : Perempuan </p>
         <p>Agama                 : Islam </p>
         <p>Alamat                : Desa tanah datar, kec. Tapung Hulu, kab. Kampar </p>
         <p>Pendidikan            : Universitas Islam Negeri Sultan Syarif Kasim Riau</p>
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
       background-color: rgb(223, 187, 214);
       border-radius: 25px;
       
     }
     .container-one{
       background: linear-gradient(rgba(86, 3, 54, 0.96), rgba(190, 60, 125, 0.9), rgba(214, 188, 204, 0.96)),center/cover no-repeat;
       width: 30%;
     }
   
     .profile img{
       background-color: rgb(195, 214, 208) ;
       height: 13rem;
       border-radius: 30%;
     }
     .link a{  
       text-decoration: none;
       color: rgb(15, 14, 14);
       font-size: 10px;
     }
     .link img{
       height: 13rem;
     }
     .container-two{
       background: linear-gradient(rgba(86, 3, 54, 0.96), rgba(190, 60, 125, 0.9), rgba(214, 188, 204, 0.96)),center/cover no-repeat;
       margin: 3%;
       margin-left: 3%;
       border-radius: 2%;
       color: antiquewhite;
       width: 80%;
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
       margin: 20px;
     }
     .project-button a{
       text-decoration: none;
       color: rgb(255, 255, 255);
     }
   
   </style>
     