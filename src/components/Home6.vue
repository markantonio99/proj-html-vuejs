<template>
  <div class="container">

                <div class="content-flex-sx">
                      <div class="content-text">
                            <p class="text-primary">SEND A MESSAGE</p>
                            <h2 class="title">Get in <span class="color_title">Touch</span> </h2>
                            <p class="text-secondary">We will respond to your message as soon as possible.</p>
                      </div>
                     

                       <form action="">
                         <div class="row">
                                <div class="col">
                         <label for="name"></label>
                         <input type="text" id="name" name="name" placeholder="Name" required>
                                </div>
                                <div class="col">
                         <div class="col">
                             <label for="email"></label>
                             <input type="email" id="email" name="email" placeholder="Email" required>
                         </div>
                                </div>  
                           </div>
                         <div class="row">
                                 <div class="col">
                                 <input type="tel" id="phone" name="phone" placeholder="Phone" required>
                          </div>
                          <div class="col">
                              <select>
                                 <option value=""> --Please  choose an option--</option>
                                 <option value="">Sales and Purchasing</option>
                                 <option value="">Financial and Accounts</option>
                                 <option value="">Spagna</option>
                                 <option value="">Subject Human Resources</option>
                                 <option value="">Another subjects</option>
                              </select>                 
                         </div>           
                         </div>

                       <div class="row">
                                     
                                        <textarea id="message" name="message" placeholder="Message"></textarea>
                                    
                          </div>
                                    <div class="row">
                                      <button type="submit">SEND</button>
                          </div>  
                       </form>
                </div>



                <div class="content-flex-dx">
                     <h3 class="title-3">Example Inc.</h3>
                     <p class="text-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                     <ul class="group_icon">
                      <li class="icon_list">
                        
                      </li>
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
                     <a class="link_map" href="#">VIEW MAP</a>

                </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .container{
      max-width: 1080px;
      margin: 0 auto;
        min-height: 500px;
        background-color: #FFFFFF;
        display: flex;
        align-items: center;

    }

    .content-flex-sx{
      flex-basis: 65%;

        .content-text{
           padding: 50px 0 50px 0;
      
        }

        .text-primary{
           color: #6ca0a0;
           font-size: 15px;
           }

           .title{
            font-size: 40px;
            padding: 20px 0;

              .color_title{
                color: #6ca0a0;
              }
           }
           .text-secondary{
                color: #455e5e;
              }


    }  

    form {
  max-width: 800px;
  margin: auto;
}
.row {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-bottom: 20px;
}
.col {
  flex-basis: 48%;
}
.col label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="text"],
input[type="email"],
input[type="tel"],
 textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 16px;
  margin-top: 5px;
  resize: vertical;
}
textarea {
  height: 150px;
}
 
button[type="submit"] {
  padding: 10px 30px;
  font-weight: 500;
  background-color: #6ca0a0;
  color: white;
  border: none;
  border-radius: 20px;
  font-size: 16px;
  cursor: pointer;
}

select {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    min-height: 39px;
    margin-top: 7px ;
    border: 1px solid rgb(200, 192, 192);
    border-radius: 5px;
    width: 335px;
}

////////////////////////////////// seconda parte
////////////////////////////////
//////////////////////////////
////////////////////////////


.content-flex-dx{
      flex-basis: 35%;
      padding-left: 70px ;

      .title-3{
        font-size: 22px;
        padding: 10px 0;
      }
      .text-3{
        font-size: 15px;
        padding: 20px 0;
        font-weight: 100;
      }

      .icon_list{
         padding: 20px 0;
         font-size: 17px;
         color: #6ca0a0;
      }

      .text_list{
        padding-left: 15px;
        font-size: 17px;
      }

      .link_map{
      display: block;
      color: #6ca0a0;
      padding-top: 30px;
      font-size: 14px;
      }

    }  

 


</style>