<template>


  <div class="container_home_3">
          <div class="section-home-3">
            
                        <div class="item_home_3">
                    <h2 class="title_home_3">The <span class="back-title">Company</span></h2>
                    <p class="text_home_3">For 12 years we have been providing audit and warranty,
                        financial advice, risk advice, taxes and related services 
                        to select clients.
                    </p>

                    <div class="card-container">
                             <div class="item_card">
                                              <span class="icon_title"><i class="fa-solid fa-hourglass-end"></i></span>
                                              <h3 class="title_card">Tradition</h3>
                                              <p class="text_card">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>
                             </div>
                             <div class="item_card">        
                                               <span class="icon_title"><i class="fa-solid fa-lock"></i></span>
                                               <h3 class="title_card">Security</h3>
                                               <p class="text_card">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>

                             </div>
                             <div class="item_card">    
                                                  <span class="icon_title"><i class="fa-solid fa-apple-whole"></i></span> 
                                                  <h3 class="title_card">Cerrtificate</h3>
                                                  <p class="text_card">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>

                             </div>
                             <div class="item_card">
                                                   <span class="icon_title"><i class="fa-solid fa-user-tie"></i></span>
                                                   <h3 class="title_card">Expertise</h3>
                                                   <p class="text_card">Lorem ipsum dolor sit amet consectetur adipiscing elit.</p>

                           </div>
                    </div>

                        </div>                    
          </div>

          <div class="section-home-4">
              <div class="item_home_4">
                  <div class="tumb_home_4">
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

.container_home_3{
    background-color: #162e48;
    min-height: 500px;
    display: flex;
    justify-content: center;
   

    .section-home-3{
       flex-basis: 70%;
       padding: 30px;
    }
    
    .item_home_3{
       flex-basis: 50% ;
       padding-left: 150px;
    }


    .title_home_3, .text_home_3, .title_card, .icon_title{
        color: white;   
    }

    .title_home_3{
        font-size: 45px;
        font-weight: 800;
        padding: 30px 0;
    }
    .back-title {
      background-color: #174953;
}


  
    .title_card, .icon_title{
        display: inline-block;
        font-size: 27px;
        padding-right: 10px;
    }

    .card-container{
        padding-top: 30px;
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        color: white;

    }
    
    .item_home_4{
        padding: 50px ;
    }

    .item_card{
        padding-top: 40px;
        flex-basis: 50%;
    }

    .text_card{
        padding: 20px 15px 20px 0;
    }

    .tumb_home_4 {
  height: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.tumb_home_4{
 padding: 150px 300px;
}
.section-home-4 {
  flex-basis: 50%;
  background-image: url('../assets/about-4.jpg');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
  max-width: 100%;
  min-height: 500px;
  background-position: 100% 0;
}



   

}

</style>