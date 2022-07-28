<template>
  <div id="container">
        
       <div id="sub_1">
          
            <img src="..//assets/home-testimonial-113165296.jpg" alt="">
          
         <h2>Specialists In Modern Constructions</h2>
         <div id="spacer"></div>
         <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia eligendi a ea, <br>
          ipsa sequi provident repellendus laudantium tempore?</p>
          <p>HARRY SMITH - NEW HOME OWNER</p>
          
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
div{
    height: 60rem;
    width: 100%;
    background-image: url('../assets/home-parallax-144609983.jpg');
    background-size: cover;
}
img{
  border-radius: 50%;
}
#spacer{
  height: .15rem;
  background-color: rgba(254,210,63,255);
  width: 10rem;
  margin-top:1rem;
}
#sub_1{
padding-top: 20rem;
display: flex;
flex-direction: column;
align-items: center;
}
#container{
  display: flex;
  color: white;
}
p{
  margin-top:2rem ;
  text-align:center;
}
</style>