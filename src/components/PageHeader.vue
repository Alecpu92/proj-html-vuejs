<script>



export default {
    name: "PageHeader",
    props: {
      links: Array,
    }

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
    <div class="container_logo">
      <div>
        <img src="../assets/img/university_logo.png" alt="">
      </div>
      <div>
       <nav>
        <ul>
          <li v-for="link in links">
            <a :href="link.url">
              {{ link.text }}
            </a>
          </li>
        </ul>
       </nav>
      </div>
    </div>
    <div class="container_image">
      
          <h1>Inspiring Tomorrow Leaders</h1>
          <h3>The Future Belongs To Those Who See Possibilities Today</h3>
          <button id="b1">FIND A COURSE</button>
           <span><button id="b2">APPLY NOW</button></span>
      
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
  margin: 0 auto;
}
.container_logo{
  width: 100%;
  height: 100px;
  background-color: white;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
a{
  text-decoration: none;
  color: black;
  font-size: 10px;
}
.container_image{
  width: 100%;
  height: 500px;
  background-color: black;
  background-image: url(../assets/img/home_main_slider_bg.jpg);
  text-align: center;
  color: white;
}


 

</style>
