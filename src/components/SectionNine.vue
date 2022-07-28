<template>
  <div id="container">
    <div id="sub1">
      <h3>Building Inspiring Spaces</h3>
      <div id="spacer"></div>
      <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Eveniet quod repellendus fugit consequuntur reprehenderit nemo dolor, <br> mollitia voluptas laborum odio vitae sint cupiditate iste culpa. </span>
    </div>
    <div id="sub2">
      <button>GET A FREE QUOTE</button>
      <span>Only takes a few seconds!</span>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#container{
    width:100%;
    height: 25rem;
    background-image: url('..//assets/about-call-to-action-57862405.jpg');
    background-size:contain;
    display: flex;
    justify-content: center;
    align-items: center;
  
}
#sub1{
  display: flex;
  flex-direction: column;
  color: white;
  margin-right: 4rem;
}
#spacer{
  width: 8rem;
  height: .15rem;
  background-color: rgba(254,210,63,255);
  margin-top: 1.5rem;
  margin-bottom: 1.5rem;
}
button{
  background-color: rgba(254,210,63,255);
  padding: 1rem 2rem 1rem 2rem;
  margin-bottom: 1rem;
  border: rgba(254,210,63,255);
}
#sub2{
  display: flex;
  flex-direction: column;
  align-items: center;
  color: white;
}
</style>