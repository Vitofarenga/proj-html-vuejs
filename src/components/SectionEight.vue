<template>
  <div id="container">
      <div id="sub_1">
          
         <h2>Trusted Partners</h2>
         <div id="spacer"></div>
         <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia eligendi a ea, <br>
          ipsa sequi provident repellendus laudantium tempore?</p>
         <div>
           <img src="..//assets/home-logo11-219096700-320x202.png" alt="">
           <img src="..//assets/home-logo10-219096700-320x202.png" alt="">
           <img src="..//assets/home-logo2-219096700-320x202.png" alt="">
           <img src="..//assets/home-logo1-219096700-320x202.png" alt="">
           <img src="..//assets/home-logo9-219096700-320x202.png" alt="">
         </div>
      </div>
      
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#container{
    height: 30rem;
    width:100%;
    background-color: white;
    display: flex;
    justify-content: center;
}

#spacer{
  height: .15rem;
  background-color: rgba(254,210,63,255);
  width: 10rem;
  margin-top:1rem;
}
#sub_1{
padding-top: 5rem;
display: flex;
flex-direction: column;
align-items: center;
}
img{
  padding-top: 3rem;
  width: 10rem;
}

p{
  margin-top:2rem ;
  text-align:center;
  line-height: 2rem;
}

</style>