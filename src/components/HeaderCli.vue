<template>
  <header>
    <div id="container">
        <div id="imgcontainer">
        <img src="../assets/construction_logo.png" alt="">
        </div>
        <ul id="list">
            <li v-for="element in elements" :key="element.element">
              <a :href="element.url">{{element.element}}</a>
            </li>
        </ul>
    </div>
  </header>
</template>

<script>
export default {
  data: function(){
    return{
    elements : [
       {element: 'HOME' },
       {element: 'ABOUT'},
       {element: 'SERVICES' },
       {element: 'WORK'},
       {element: 'ARTICLES' },
       {element: 'GET QUOTE',
       url: '#'},
    ]
  }
}
}

</script>

<style scoped>
#container{
    height: 7rem;
    width: 100%;
    background-color: white;
    display: flex;
    justify-content: space-between;
    
}
img{
    width:12rem;
    height: 4rem;
}
#imgcontainer{
    height: 100%;
    display: flex;
    align-items: center;
    margin-left: 5rem;
}
ul{
    list-style: none;
    display: flex;
    margin-right: 5rem;
    
}
li{
    
    margin-left: 2rem;
    display: flex;
    height: 100%;
    align-items: center;
    font-size: .8rem;
    color: rgba(188,188,188,255);
}
a{
    text-decoration: none;
}


</style>