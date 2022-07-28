<template>
  <div>
     <ul id="ul1">
      <li><img src="..//assets/construction_logo.png" alt=""></li>
      <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Obcaecati placeat pariatur molestiae non iure odit excepturi nisi nesciunt alias, earum exercitationem in eius minus, commodi inventore provident vitae, quae itaque.</li>
      <li><button>LEARN MORE</button></li>
     </ul>
     <ul>
      <li class="title">LATEST TWEETS</li>
      <li>
        
           <img src="..//assets/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="" id="littleimg">
           <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam magni illo provident voluptatem fuga necessitatibus pariatur maiores modi temporibus, mollitia accusamus culpa rerum earum blanditiis laudantium ratione architecto quaerat! Maxime.</span>
        
      </li>
      <li><img src="..//assets/En2TRxLW4AEiWUN.jpeg" alt="" id="off"></li>
     </ul>
      <ul>
        <li class="title">CONTACT US TODAY</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
      </ul>
     <ul>
      <li class="title">FIND US</li>
      <li><img src="..//assets/construction_map_pin.png" alt="" id="map"></li>
     </ul>
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
    background-color: rgba(30,30,30,255);
    display: flex;
    justify-content: space-around;
    padding-left: 5rem;
    padding-right: 5rem;
}
button{
  
  background-color: rgba(254,210,63,255);
  padding: .5rem 2rem .5rem 2rem;
  margin-bottom: 1rem;
  border: rgba(254,210,63,255);
  color: rgba(107,104,104,255);
}
#off{
  width: 17rem;
}
.title{
  color: rgba(254,210,63,255);
}
li{
  padding: 1rem;
  display: flex;
  
}
#map{
  width: 17rem;
  height: 15rem;
}
ul{
  list-style: none;
  width: 17rem;
}
#ul1{
  color: rgba(107,104,104,255);
}
#littleimg{
  width: 2rem;
  height: 2rem;
  border-radius: 50%;
  margin-right: 1rem;
}
</style>

