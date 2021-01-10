<template>
    <div>
       <nav class="navbar navbar-expand-lg navbar-light bg-primary">
  <a class="navbar-brand" href="#">Magallon's  </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button> 
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <router-link to="/">
      <li class="nav-item active">
        <a class="nav-link text-white" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      </router-link>
      <router-link to="/about">
      <li class="nav-item">
        <a class="nav-link text-white" href="#">About</a>
      </li>
      </router-link>
       <router-link to="/services">
      <li class="nav-item">
        <a class="nav-link text-white" href="#">Services</a>
      </li>
      </router-link>
       <router-link to="/contact">
       <li class="nav-item">
        <a class="nav-link text-white" href="#">Contact</a>
      </li>
       </router-link>
      
  
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-dark my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
    </div>    
</template>

<script>
export default {
    name: 'Navigation'
}
</script>

  
  
<style scoped>
 a{
  text-decoration: none;
}


.navbar-nav a:hover {
  opacity: 0.9; 

}
</style>