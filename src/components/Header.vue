<template>
  <header class="container-header">
                       <div class="flex-top-header">
                            
                               <div class="item_top_header">
                                       <i class="fa-solid fa-clock"></i>                            
                                       <span class="cont_sx">Open Hours: Mon - Sat - 9:00 - 18:00</span>
                               </div>

                                <div class="item_top_header">
                                        <div class="cont_dx">
                                            <div> 
                                                        <i class="fa-solid fa-phone"></i>
                                                         <span class="cont_sx">+1 (305) 1234-5678</span>
                                              </div>
                                              <div>
                                                         <i class="fa-solid fa-envelope"></i>
                                                         <span class="cont_sx">hello@example.com</span>
                                              </div>
                                              <div class="group_icon">
                                                <i class="fa-brands fa-facebook-f"></i>
                                                <i class="fa-brands fa-twitter"></i>
                                                <i class="fa-brands fa-linkedin"></i>
                                              </div>              
                                        </div>
                                    
                                                
                                             

                                 </div>
                                 
                                                
                        </div>    <!-- flex-top-header -->
                        <!-- /////// fine top-bar -->


                        <div class="main_header">
                                    <div class="container_header">
                                         <div class="item-cont-head">
                                            <figure>
                                                          <img class="logo_head" src="../assets/logo.PNG" alt="">
                                            </figure>
                                            <nav>
                                                           <ul class="main-page">
                                                            <li>Demos</li>
                                                            <li>Pages</li>
                                                            <li>Portafolio</li>
                                                            <li>Blog</li>
                                                            <li>Shop</li>
                                                            <li class="btn_head">
                                                                <a href="#">GET IN TOUCH</a>
                                                            </li>
                                                           </ul>
                                            </nav>
                                            <div class="central-main-block">
                                                   <h2><span style="background-color:#DADDE1">Ready</span>  <span style="color: #058283">Team</span></h2>
                                                            <p class="text_central_block">Lorem ipsum dolor architecto voluptatum quaerat dolor architecto 
                                                              distinctio fugiat!
                                                            </p>
                                                            <button>GET IN TOUCH</button>
                                            </div>
                                            
                                         </div>

                                    </div>

                                    
                                   

                        </div>
  </header>
</template>

<script>
import { library } from '@fortawesome/fontawesome-svg-core'

export default {

}
</script>

<style lang="scss" scoped>



.flex-top-header{
   background-color: #143349;
   display: flex;
   justify-content: center;
   padding: 15px 0;
 

   .item_top_header{
    flex-basis: 50%;
    text-align: center;
   }

     

       .item_top_header, .cont_sx{
          color: #04A5A6;
       } .cont_sx{
        margin-left: 10px;
       }


       .cont_dx{
        display: flex;
        justify-content: center;
        gap: 30px;
       }

       .group_icon{
        display: flex;
        gap: 20px
       }
}

.container_header{
    margin: 0 auto;
    background-color: #EEEFEF;
    min-height: 1000px;
    background-image: url('../assets/bg-parallax.png');
    background-position: center top -120px;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;


    .item-cont-head{
        padding: 15px 0;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 250px;
    
        
    }


    .logo_head{
        max-width: 140px;
       
       
    }

    .main-page{
        display: flex;
        align-items: center;
        gap: 30px;
        font-size: 20px;
    }

    .btn_head{
        background-color: #058283;
        padding: 10px;
        color: white;
         
    }
     

    .central-main-block{
        color: #21333E;
        font-size: 3.7rem;
        position: absolute;
        top: 30%;
        font-family: 'Roboto', sans-serif;
        font-weight: 900; 
        text-align: center;
    }
     

    .text_central_block{
        font-size: 20px;
        text-align: center;
        font-weight: 300;
        color: #04A5A6;
        padding: 20px 620px;
    }

    button{
        background-color: #058283;
        font-size: 17px;
        color: white;
        padding: 13px 35px;

    }


}




</style>