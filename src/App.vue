<template>
  <div id="app">
    <div id="nav">

<nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    
    <a class="navbar-brand"  href=""> <img src="./assets/logo.png"  alt=""></a> 

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
       <ul class="navbar-nav">
        <li class="nav-item">
           <a class="nav-link " href="#">
           <router-link to="/">Home</router-link> </a>
          
        </li>
        <li class="nav-item">
           <a class="nav-link" href="#">
            <router-link to="/about">About</router-link> </a>    
        </li>
        <li class="nav-item">
           <a class="nav-link" href="#">
            <router-link to="/Services">Services</router-link> </a>    
        </li>
        <li class="nav-item">
           <a class="nav-link" href="#">
            <router-link to="/Products">Products</router-link> </a>    
        </li>
        <li class="nav-item">
           <a class="nav-link" href="#">
            <router-link to="/Team">Team</router-link> </a>    
        </li>
        <li class="nav-item">
           <a class="nav-link" href="#">
            <router-link to="/contact">Contact</router-link> </a>    
        </li>
     
       
      </ul>
    </div>
  </div>
</nav>
   
    </div>
    <router-view/>
  </div>
</template>
<script>

</script>
<style lang="scss">
#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  // -webkit-font-smoothing: antialiased;
  // -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {

  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration:none ;
    

    &.router-link-exact-active {
      color: #42b983;
      font-family: 'Courier New', Courier, monospace;
     background-color: #2b3947;
     border: none;
     color: white;
      font-style: italic;
     padding: 5px 32px;
     text-align: center;
     font-size: 16px;
     margin: 4px 2px;
     opacity: 0.8;
     transition: 0.3s; 
    }
  }
}
</style>
