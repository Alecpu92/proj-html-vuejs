<script>



export default {
    name: "PageHeader",

}
</script>

<template>
  <header>
    <div class="container_start">
      <div>
        <ul>
          <li>1.800.900.900 <i class="fa-solid fa-phone-flip"></i> 24h </li>
          <li> <i class="fa-solid fa-envelope"></i> Contact us </li>
          <li><i class="fa-solid fa-graduation-cap"></i> Alumni</li>
          <li><i class="fa-solid fa-house"></i> Campus</li>
        </ul>
      </div>
      <div>
        <ul>
          <li><i class="fa-brands fa-facebook"></i></li>
          <li><i class="fa-brands fa-instagram"></i></li>
          <li><i class="fa-brands fa-youtube"></i></li>
          <li><i class="fa-brands fa-twitter"></i></li>
        </ul>
      </div>
    </div>
  </header>




  
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as *;

.container_start{
  width: 100%;
  height: 50px;
  background-color: orange;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  
}
ul{
  display: flex;
  flex-direction: row;
  color: white;
  font-size: 10px;
  list-style-type: none; 
  
}
li{
  padding: 20px;
}
 

</style>
