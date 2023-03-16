 <template>
   <div class="container">
         <div class="section-background">
                            <div class="section-home-5">

                                                      <div class="item-home-5-content-up">
                                                                      <h1 class="title-section">Results in Numbers</h1>
                                                                      <p class="text-section">Our goal is to exceed expectations by delivering the best job possible.</p>
                                                                      <div class="flex-group-tex">
                                                                               <div class="item-group-tex">
                                                                                          <ul class="number-flex">
                                                                                            <li>128 <br><span class="sut_titl">Certification</span></li>
                                                                                            <li>230 <br><span class="sut_titl"> Employees</span></li>
                                                                                            <li>517 <br><span class="sut_titl">Customer</span></li>
                                                                                            <li>94 <br><span class="sut_titl">Countries Served</span></li>

                                                                                          </ul>
                                                                               </div>

                                                                      </div>
                                                       </div>

                                                       <div class="item-home-5-content-down">
                                                                       <div class="background">
                                                                              <img src="../assets/bullets.png" alt="">
                                                                       </div>
                                                                       <figure class="content-baseline-home-5">
                                                                              <img class="items-logo" src="../assets/logo-1.png">
                                                                              <img class="items-logo" src="../assets/logo-2.png">
                                                                              <img class="items-logo" src="../assets/logo-3.png">
                                                                              <img class="items-logo" src="../assets/logo-4.png">
                                                                              <img class="items-logo" src="../assets/logo-5.png">
                                                                              <img class="items-logo" src="../assets/logo-1.png">
                                                                       </figure>
                                                       </div>

                            </div>
                        

         </div>
         


   </div>

   
 </template>
 
 <script>
 export default {
 
 }
 </script>
 
 <style lang="scss" scoped>
 .container{
    margin: 0 auto;
}
.section-background {
  background-image: url('../assets/bg-7.jpg');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  min-width: 100%;
  min-height: 300px;
  background-position: 100% 0;
}
//////////////////////      Inizio contenitori
///////////////////////////
/////////////////////////
///////////////////////
//////////////////////
///////////////////
/////////////////




.item-home-5-content-up{
  text-align: center;
  font-weight: 800;
  color: white;
  padding: 40px 0;   

        
       .title-section{
        font-weight: 900;
        font-size: 45px;
       }


        .text-section{
            padding: 30px;
            font-weight: 300 ;
        }       

        .number-flex{
               display: flex;
               justify-content: center;
               gap: 130px;
               font-size:35px;
               padding: 40px;
               color: #6ca0a0;
        }
        .sut_titl{
            font-size: 15px;
            font-weight: 300;
        }
}

.item-home-5-content-down{
    background-color: #12232F;
    min-height:200px;
    position: relative;
   


    .content-baseline-home-5{
       display: flex;
       justify-content: center;
       align-items: center;
       align-content: center;
       gap: 40px;
       filter: invert(1);
       max-width: 200px;
       margin: 0 auto;


      
    }

    .background{
        width: 50px;
        opacity: 50%;
        position: absolute;
        left: 50%;
        top: -10%;
        
    }

    .items-logo{
       max-width: 100%;
       padding: 60px;
    }




}
 
 </style>