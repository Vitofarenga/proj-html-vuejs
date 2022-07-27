<template>
  <div>
    <div id="sub_1">
         <h2>OUR CORE VALUES</h2>
         <div id="spacer"></div>
         <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officia eligendi a ea, <br>
          ipsa sequi provident repellendus laudantium tempore?</p>
          <div id="cardcont">
             <div class="card" v-for="card in cards" :key="card.image">
                 <div class="circle"></div>
                 <span>{{card.title}}</span>
                 <div class="spacer2"></div>
                 <span>{{card.topic}}</span>
             </div>
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
       title:'lorem',
       topic:'aaaaaaaaaaaaaaaaaaaaaaa' },
       {image: 'HOME',
       title:'lorem',
       topic:'aaaaaaaaaaaaaaaaaaaaaaa' },
       {image: 'HOME',
       title:'lorem',
       topic:'aaaaaaaaaaaaaaaaaaaaaaa' },
       {image: 'HOME',
       title:'lorem',
       topic:'aaaaaaaaaaaaaaaaaaaaaaa' },
    ],
  }
}
}
</script>

<style scoped>
div{
    height: 35rem;
    width: 100%;
    background-color: rgba(240,237,230,255);
}
.spacer2{
  width: 1rem;
  height: .15rem;
  background-color: grey;
  margin-top:1rem;
  margin-bottom: 1rem;
}
#sub_1{
padding-top: 5rem;
display: flex;
flex-direction: column;
align-items: center;
}
#cardcont{
  width: 100%;
  display: flex;
  margin-top: 3rem;
  padding-left:20rem ;
  padding-right: 20rem;
}
.circle{
  width:6rem ;
  height: 6rem;
  border-radius: 50%;
  border: 0.1rem solid grey;
  margin-bottom:1rem;
}
#spacer{
  height: .15rem;
  background-color: rgba(254,210,63,255);
  width: 10rem;
  margin-top:1rem;
}
p{
  text-align: center;
  margin-top: 2rem;
}
.card{
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>