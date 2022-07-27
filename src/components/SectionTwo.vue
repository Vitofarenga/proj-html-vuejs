<template>
  <div id="container">
    <div id="sub_1">
      <h2>Specialists In Modern Constructions</h2>
      <div id="spacer"></div>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia eligendi a ea, <br>
       ipsa sequi provident repellendus laudantium tempore?</p>
    </div>
    <div id="cardcontainer">
      <div class="card" v-for="card in cards" :key="card.image">
         <div class="circle"></div>
         <span class="title">{{card.title}}</span>

         <span class="topic">{{card.topic}}</span>
      </div>
    </div>
    
     
  </div>
</template>

<script>
export default {
 data: function(){
    return{
    cards : [
       {image: 'HOME',
       title: 'Buildings',
       topic: 'aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa' },
       {image: 'ABOUT',
       title: 'Renovate',
       topic: 'aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa' },
       {image: 'SERVICES',
       title: 'Construct',
       topic: 'aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa' },
       {image: 'WORK',
       title: 'Exclusive',
       topic: 'aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa' },
    ]
  }
}
}
</script>

<style scoped>
#container{
  height: 40rem;
  background-color: white;
  border-left: 10rem;
  border-bottom: 30rem;
  display: flex;
  align-items: center;
  flex-direction: column;
}
h2{
  color: black;
}
#sub_1{
margin-top: 3rem;
display: flex;
flex-direction: column;
align-items: center;
}
.title{
  font-size: 2rem;
}
h2{
  color:rgba(49,49,47,255);
}
#spacer{
  height: .15rem;
  background-color: rgba(254,210,63,255);
  width: 10rem;
  margin-top:1rem;
}
#cardcontainer{
  display: flex;
  width: 100%;
  height: 20rem;
  margin-top: 3rem;
  background-color:red;
  align-items: center;
  padding-left:2rem;
}
p{
  text-align: center;
  margin-top: 2rem;
  color: grey;
}
.card{
  height: 15rem;
  background-color: white;
  width: 20rem;
  border-radius:1rem;
  display: flex;
  flex-direction: column;
  justify-items: center;
  align-items: center;
  margin-left:2rem;
  
}
.circle{
  border: .1rem solid grey;
  height: 3rem;
  width: 3rem;
  margin-top: 1rem;
  border-radius:50%;
}
span{
 padding-left: 1rem;
 padding-right: 1rem;
 word-break: break-all;
 text-align: center;
 color: rgba(188,188,188,255);
 padding-top: 1.5rem;
}
</style>