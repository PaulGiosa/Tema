<template>
  <div id="app">
    <nav>
      <figure>
        <img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTct01PK0ylQKeDyQyqzQFabAfyAHqrxuJ2mw&usqp=CAU"></img>
      </figure>
      <div class="nav-links">
        <router-link to="/">Home</router-link> 
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
      </div>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 20px;
  padding-top: 0px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  
  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;
    color: red;
    margin-left: 10px;
  
  }
  img {
    width: 50px;
  }
  
}
</style>
