<template>
  <div class="container">
  <h1 class="title-home-4">Action & <span class="background-title">Projects</span></h1>
   <ul class="flex-menu">
    <li class="items_menu active">
           ALL
    </li>
    <li class="items_menu">
          ENVIROMENT
    </li>
    <li class="items_menu">
         EVENTS
    </li>
    <li class="items_menu">
         INSTITUTIONAL
    </li>
    <li class="items_menu">
        SOCIAL
    </li>
    <li class="items_menu">
        THECNOLOGY
    </li>
    <li class="items_menu">
         INNOVATION
    </li>
   </ul>


  <div class="card-container">
    <div class="card">
      <h3 class="title_card">Portafolio item whit intro whidebar</h3>
      <img src="../assets/project-1.jpg">
    </div>
    <div class="card">
        <h3 class="title_card">President's speech at the annual meeting</h3>
      <img src="../assets/project-2.jpg">
    </div>
    <div class="card">
        <h3 class="title_card">International business item whit </h3>
      <img src="../assets/project-3.jpg">
    </div>
    <div class="card">
        <h3 class="title_card">Donation business item whit </h3>
      <img src="../assets/project-4.jpg">
    </div>
    <div class="card">
        <h3 class="title_card">International business item whit </h3>
      <img src="../assets/project-5.jpg">
    </div>
    <div class="card">
        <h3 class="title_card">International business item whit </h3>
      <img src="../assets/project-6.jpg">
    </div>
  </div>
</div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .container {
       min-height: 400px;
       background-color: #E1E3E7
      
}


.title-home-4{
    font-size: 60px ;
    color: #0D1B2A;
    text-align: center;
    padding: 130px 0 50px 0;
    font-weight: 900px;

}
.background-title{
    color: #058283;
    background-color: #D9EBED ;
    
}

.flex-menu{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 40px;
    padding-bottom: 40px;
}

.items_menu{
    font-size: 20px ;
}
   
.active{
    background-color: #b8d3d6;
    padding: 10px;
}










.card-container {
  max-width: 1400px;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-top: 20px;
  gap: 30px
}

.card {
  position: relative;
  width: 400px;
  height: 340px;
  margin: 20px;
  overflow: hidden;
  border-radius: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  top: 0;
  left: 0;
}
.title_card{
    position: absolute;
    left: 50%;
    bottom: 0%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 30px;
    z-index: 1;
    width: 80%;
    text-align: center;
}


.card {
  position: relative;
  width: 400px;
  height: 340px;
  margin: 20px;
  overflow: hidden;
  border-radius: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}




</style>