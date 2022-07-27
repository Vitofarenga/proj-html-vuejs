<template>
  <div>
     <div id="slider">
      <h1>BUILDING INSPIRING SPACES</h1>
      <span>We Build Inspiring Residential & Commercial Spaces</span>
      <div id="buttonscontainer">
        <button id="greybutton">EXPLORE RECENT WORK</button>
        <button id="yellowbutton">GET A QUOTE TODAY</button>
      </div>
     </div>
     <div id="littleyellow">
        <h2>Do You Have A Construction Project We Can Help You With?</h2>
        <div id="buttoncontainer"><button id="getquote">GET A FREE QUOTE</button></div>
     </div>
  </div>
</template>

<script>
export default {

}

</script>

<style scoped>
h2{
  margin-bottom:1.2rem;
  color:rgba(49,49,47,255);
}
#slider{
    background-image: url('../assets/home-slider-62528242.jpg');
    background-size: cover;
    height: 40rem;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
#buttonscontainer{
  margin-top:2.3rem;
}
#greybutton{
color: white;
  background-color: rgba(49,49,47,255);
  border-color: rgba(49,49,47,255);
  padding: .5rem 2rem .5rem 2rem;
  top: 5.5rem;
}
#yellowbutton{
  border-color: rgba(254,210,63,255);
  color: white;
  background-color: rgba(254,210,63,255);
  padding: .5rem 2rem .5rem 2rem;
  top: 5.5rem;
  margin-left: .5rem;
}
#littleyellow{
    height: 7rem;
    width: 100%;
    background-color: rgba(254,210,63,255);
    color: rgba(102,102,101,255);
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
}
span{
  color: rgba(254,210,63,255);
  font-size: 1.5rem;
  margin-top:1.5rem;
}
h1{
  color:white;
  font-weight: bold;
  font-size: 3rem;
}
#getquote{
  color: white;
  background-color: rgba(49,49,47,255);
  border: .15rem solid white;
  padding: 1rem 2rem 1rem 2rem;
  position:absolute;
  top: 5.5rem;
  left:40rem;
}
#getquote:hover{
  color: rgba(49,49,47,255);
  background-color: white;
  border: .15rem solid rgba(49,49,47,255);
}


</style>