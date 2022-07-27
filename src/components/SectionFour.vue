<template>
  <div id="container">
      <div id="sub_1">
         <h2>Specialists In Modern Constructions</h2>
         <div id="spacer"></div>
         <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia eligendi a ea, <br>
          ipsa sequi provident repellendus laudantium tempore?</p>
          <div id="cont2">
            <div class="imcont" >
             <img src="..//assets/project1-featured-294276386.jpg" alt="">
             <img src="..//assets/project2-featured-15013609.jpg" alt="">
             <img src="..//assets/project3-featured-189023420.jpg" alt="">
            </div>
          </div>
          <div id="viewprojects">
            <div class="spacer2 left"></div>
            <span>VIEW ALL PROJECTS</span>
            <div class="spacer2 rigth"></div>
          </div>
      </div>
      
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
div{
    height: 40rem;
    width: 100%;
    background-color: white;
}
span{
  padding-top: .5rem;
}
#viewprojects{
  display: flex;
  width: 100%;
  justify-content: center;
  margin-top: 4rem;
}
.left{
  margin-right: 4rem;
}
.rigth{
  margin-left: 4rem;
}
.spacer2{
  height: .15rem;
  background-color: grey;
  width: 17.5rem;
  margin-top:1rem;
}
#cont2{
  display: flex;
}
#sub_1{
margin-top: 3rem;
display: flex;
flex-direction: column;
align-items: center;
}
#spacer{
  height: .15rem;
  background-color: rgba(254,210,63,255);
  width: 10rem;
  margin-top:1rem;
}
p{
  text-align:center;
  margin-top: 2rem;
}
.imcont{
  display: flex;
  width:100%;
  height: 15rem;
  justify-content: space-around;
  margin-top: 4rem;
  padding-left:20rem ;
  padding-right:20rem ;
}
img{
  width: 17rem;
  height: 17rem;

}
</style>