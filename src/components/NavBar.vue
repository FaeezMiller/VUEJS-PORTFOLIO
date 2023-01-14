<template>
   <nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
    <!-- Avatar image in top left corner -->
    <img src="https://i.postimg.cc/0j6Ss9NY/mr-robot.jpg" class="mrrobot" style="width:100% ">


    <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
      
      <h3>HOME</h3>
    </a>
    <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-black">
      
      <h3>ABOUT</h3>
    </a>
    
     <a href="#testimonials" class="w3-bar-item w3-button w3-padding-large w3-black">
      
      <h3>TESTIMONIALS</h3>
    </a>
    <a href="#projects" class="w3-bar-item w3-button w3-padding-large w3-black">
      
      <h3>PROJECTS</h3>
    </a>
    <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-black">
      
      <h3>PHOTOS</h3>
    </a>
    <a href="#resume" class="w3-bar-item w3-button w3-padding-large w3-black">
      
      <h3>RESUME</h3>
    </a>
    <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-black">
      
      <h3>CONTACT</h3>
    </a>
  <!-- Navbar -->
  <div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
    <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
      <a href="#home" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
      <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
      <a href="#testimonials" class="w3-bar-item w3-button" style="width:25% !important">TESTIMONIALS</a>
      <a href="#projects" class="w3-bar-item w3-button" style="width:25% !important">PROJECTS</a>
      <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
      <a href="#resume" class="w3-bar-item w3-button" style="width:25% !important">RESUME</a>
      <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
    </div>
  </div>
  </nav> 
</template>

<style>
 .mrrobot{
       height: 32%;
  }
  
</style>

<script>
export default{
    name:'NavBar'
}
</script>