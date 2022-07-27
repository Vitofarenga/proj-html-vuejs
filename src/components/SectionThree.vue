<template>
  <div id="cont">
    <div class="info" v-for="info in infos" :key="info.image">
      <span>{{info.image}}</span>
      <span class="number">{{info.number}}</span>
      <p>{{info.topic}}</p>
    </div>
  </div>
</template>

<script>
export default {
    data: function(){
    return{
    infos : [
       {image: 'HOME',
       number:'3534',
       topic:'PLANNING APPLCATION' },
       {image: 'HOME',
       number:'896',
       topic:'COMPLETED PROJECTS' },
       {image: 'HOME',
       number:'172',
       topic:'TRAINED PROFESSIONALS' },
       {image: 'HOME',
       number:'19',
       topic:'INTERNATIONAL OFFICES' },
    ],
  }
}
}
</script>

<style scoped>
.number{
  font-size: 3rem;
}
#cont{
    width: 100%;
    height: 40rem;
    background-image: url('..//assets/home-244125289.jpg');
    background-size: cover;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding-right: 20rem;
    padding-left: 20rem;
}
.info{
  width: 10rem;
  height: 5rem;
  display: flex;
  flex-direction: column;
  color: rgba(254,210,63,255);
  text-align: center;
}
</style>