<template>
  <main>
          <div class="container">
                      <div class="flex-primary-section">
                                  
                                    <div class="item-sez-title">
                                          <h2 class="title-sez-2">Excellence in <span class="service">Services</span> </h2>
                                          <p class="text-sez-2">We are leaders in providing consultancy services with a set of cutting-edge technologies and a team of experienced and renowned professionals. These are some options that you can hire.</p>
                                    </div>
                                    <div class="item_btn">                                    
                                           <a class="btn_primary" href="#">SEE ALL</a>                            
                                    </div>
                                                 
                       </div>

                       <div class="conteiner-card">
                              <div class="item-card">
                                       <div class="flex_icon_card">
                                        <i class="fa-solid fa-sitemap"></i>    
                                        <i class="fa-solid fa-arrow-right"></i>
                                       </div>
                                       <h3 class="title_card">Audit & Assurance</h3>
                                       <p class="text_card">Lorem ipsum dolor laboriosam quas similique aperiam ali uas similique</p>
                              </div>
                              <div class="item-card">
                                       <div class="flex_icon_card">
                                        <i class="fa-solid fa-briefcase"></i>   
                                        <i class="fa-solid fa-arrow-right"></i>
                                       </div>
                                       <h3 class="title_card">Financial Advisor</h3>
                                       <p class="text_card">Lorem ipsum dolor laboriosam quas similique aperiam ali uas similique</p>
                              </div>
                              <div class="item-card">
                                       <div class="flex_icon_card">
                                        <i class="fa-solid fa-chart-simple"></i>   
                                        <i class="fa-solid fa-arrow-right"></i>
                                       </div>
                                       <h3 class="title_card">Analictys and M&A</h3>
                                       <p class="text_card">Lorem ipsum dolor laboriosam quas similique aperiam ali uas similique</p>
                              </div>
                              <div class="item-card">
                                       <div class="flex_icon_card">
                                        <i class="fa-solid fa-plane-departure"></i>   
                                        <i class="fa-solid fa-arrow-right"></i>
                                       </div>
                                       <h3 class="title_card">Middle Marketing</h3>
                                       <p class="text_card">Lorem ipsum dolor laboriosam quas similique aperiam ali uas similique</p>
                              </div>
                              <div class="item-card">
                                       <div class="flex_icon_card">
                                        <i class="fa-solid fa-globe"></i>    
                                        <i class="fa-solid fa-arrow-right"></i>
                                       </div>
                                       <h3 class="title_card">Legal Consulting</h3>
                                       <p class="text_card">Lorem ipsum dolor laboriosam quas similique aperiam ali uas similique</p>
                              </div>
                              <div class="item-card">
                                       <div class="flex_icon_card">
                                        <i class="fa-solid fa-inbox"></i> 
                                        <i class="fa-solid fa-arrow-right"></i>
                                       </div>
                                       <h3 class="title_card">Regulatory Risk</h3>
                                       <p class="text_card">Lorem ipsum dolor laboriosam quas similique aperiam ali uas similique</p>
                              </div>
                       </div>

           
          </div>
   </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

main{
    background-color: #E1E3E7;
    position: relative;
    margin-top: -110px;
    min-height: 850px;

    .container{
        max-width: 1080px;
        margin: 0 auto

    }
    .flex-primary-section{
        display: flex;
        align-items: end;
        
    }

    .item-sez-title{
        flex-basis: 80%;
        padding-top: 40px;

    }

    .item_btn{
        flex-basis: 20%;
       text-align: end;

    }

    .btn_primary{
        color: white;
        background-color: #938289;
        padding: 10px 20px;
        border-radius: 5px ;
        
        
    }
    .title-sez-2{
        font-size: 50px;
        padding-top: 40px;
        font-family: 'Inter', sans-serif;
        font-weight: 900;
        color: #21333E;
     }
        .service{
            color: #058283;
            background-color: rgb(199, 217, 223, 0.7);
        }
           .text-sez-2{
            color: #584d51;
            padding: 25px 100px 0 0 ;
            font-size: 18px;
            font-weight: 400;      
           }
}

.conteiner-card{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
    padding-top: 40px ;
    
      
    .item-card{
        flex-basis: 32%;
        border: 1px solid rgba(255, 0, 0, .1);
        padding: 20px;
        background-color: rgba(255, 255, 255, 0.1 );
    }

    .flex_icon_card{
        display: flex;
        justify-content: space-between;
        font-size: 25px;
        padding: 20px 0;
    }

    .title_card{
        font-size: 25px;
    }
    .text_card{
        padding: 15px 140px 10px 0;
        font-size: 17px ;
    }
}


</style>