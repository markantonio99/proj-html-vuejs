<template>
    <footer class="container">

         <div class="section_footer">
            <div class="flex_content">
                    </div>
                     <div class="items-contente">
                             <figure class="logo">
                                <img class="color_tumb" src="../assets/logo.PNG" alt="">
                             </figure>
                             <p class="text_foot_1"></p>
                             <ul class="group_icon">
                                  <li class="icon_list">
                                           <i class="fa-solid fa-phone"></i>
                                           <span class="text_list">+1 (305) 1234-5678</span> 
                                  </li>
                                  <li class="icon_list">
                                           <i class="fa-solid fa-envelope"></i> 
                                           <span class="text_list"> mail@example.com</span> 
                                  </li>
                                  <li class="icon_list">
                                           <i class="fa-solid fa-location-dot"></i>
                                           <span class="text_list"> Main Avenue, 123</span> 
                                  </li>
                                  <li class="icon_list">
                                           <i class="fa-solid fa-location-dot"></i>
                                           <span class="text_list"> Main Avenue, 987</span> 
                                  </li>
                                 </ul>
                                 <a class="clt_action" href="#"> BUY NEXGEN</a>

                     </div>

                     <div class="items-contente-card">
                        <h2 class="title_card_footer">Company</h2>
                        <ul class="group_text_footer">
                            <li class="list_footer_card">
                                Institutional
                            </li>
                            <li class="list_footer_card">
                                Social & Events
                            </li>
                            <li class="list_footer_card">
                                Innovation
                            </li>
                            <li class="list_footer_card">
                                Environment
                            </li>
                            <li class="list_footer_card">
                                Technology
                            </li>
                        </ul>

                     </div>

                     <div class="items-contente-card">
                        <h2 class="title_card_footer">Company</h2>
                        <ul class="group_text_footer">
                            <li class="list_footer_card">
                                Institutional
                            </li>
                            <li class="list_footer_card">
                                Social & Events
                            </li>
                            <li class="list_footer_card">
                                Innovation
                            </li>
                            <li class="list_footer_card">
                                Environment
                            </li>
                            <li class="list_footer_card">
                                Technology
                            </li>
                        </ul>

                     </div>

                     <div class="items-contente-card">
                        <h2 class="title_card_footer">Company</h2>
                        <ul class="group_text_footer">
                            <li class="list_footer_card">
                                Institutional
                            </li>
                            <li class="list_footer_card">
                                Social & Events
                            </li>
                            <li class="list_footer_card">
                                Innovation
                            </li>
                            <li class="list_footer_card">
                                Environment
                            </li>
                            <li class="list_footer_card">
                                Technology
                            </li>
                        </ul>

                     </div>
         </div>   
         
         <div class="container-down-footer">
            <div class="botton-footer">
                    <p class="text_down_footer">© 2023 - All rights reserved. Nexgen is maintained by Codings Group.</p>
                    <ul class="group_icon_footer_down">
                        <li class="icon_list">
                            <i class="fa-brands fa-facebook-f"></i>
                        </li>
                        <li class="icon_list">
                            <i class="fa-brands fa-twitter"></i>
                        </li>
                        <li class="icon_list">
                            <i class="fa-brands fa-linkedin"></i>
                        </li>
                    </ul>
         </div>
         </div>
        

    </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>


.container{
    background-color: #11283A;
}
.section_footer{
    max-width: 1280px;
    display: flex;
    align-items: center;
    gap: 20px;
}

.flex_content{
    flex-basis: 25%;
   
}
.items-contente{
    padding: 50px 0;
    color: white;

}
.logo{
    width:40%;
    padding: 20px 0;
}
.color_tumb{
    color: white;
}
.icon_list{
    padding: 10px 0;
    color: rgb(206, 188, 188);
}
.text_list{
    padding-left: 10px;
}
.clt_action{
    font-size: 15px;
    margin-top: 20px ;
    display: inline-block;
    color: white;
    padding: 10px 15px;
    border: 1px solid white;
    border-radius: 15px;
    border-color: rgb(206, 188, 188, 0.7);
}


////////////////////////// 2 card
///////////////////////
////////////////////


.items-contente-card{
    flex-basis: 25%;
    color: white;
    background-color: rgba(224, 222, 230, 0.08);
    padding: 30px 35px;
} .title_card_footer{
    font-size: 22px;
    padding: 10px 0;    
 
}
.list_footer_card{
        padding: 7px 0;
        color: rgb(206, 188, 188);
    } 


.container-down-footer{
    
    background-color: rgba(224, 222, 230, 0.08);

}

 .botton-footer{
    max-width: 1080px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
    padding: 8px 0;

    .text_down_footer{
        font-size: 13px;
        color: white;
    }
    .group_icon_footer_down{
        display: flex;
        gap: 26px;
        padding-right: 50px ;
       font-size: 13px;
    }
 }   



</style>