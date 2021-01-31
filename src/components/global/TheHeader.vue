<template>
<nav class="navbar navbar-expand-lg navbar-light bg-white text-black">
  <div class="container">
    <img src="../../assets/images/logo.png" class="navbar-brand">
    <button class="border-0 navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
<!--      <span class="navbar-toggler-icon"></span>-->
        <i @click="ToggleAclass()" id="icon" class="fas fa-bars"></i>
    </button>
    <div class="collapse text-center navbar-collapse justify-content-center" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li @click="hidenav()" class="nav-item">
          <router-link class="nav-link" to="/" exact>Accueil</router-link>
        </li>
        <li @click="hidenav()" class="nav-item">
          <a data-scroll class="nav-link" href="">Produits</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Télécharger
          </a>
          <ul @click="hidenav()" class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
            <li><router-link class="dropdown-item" to="/telecharger">Flex POS Point de vente</router-link></li>
            <li><router-link class="dropdown-item" to="/telecharger">Flex CS Gestion commerciale</router-link></li>
            <li><router-link class="dropdown-item" to="/telecharger">Flex PMS Système de gestion hôtelière</router-link></li>
            <li><router-link class="dropdown-item" to="/telecharger">Flex XM Solution ERP/GMAO</router-link></li>
            <li><router-link class="dropdown-item" to="/telecharger">Flex Paie</router-link></li>
          </ul>
        </li>
        <li @click="hidenav()" class="nav-item">
          <router-link class="nav-link" to="/contactez-nous">Contactez nous</router-link>
        </li>          
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
        name: "NavBar",
        methods: {
            hidenav() {
            
                document.getElementById("navbarNavDropdown").classList.remove("show");
        },
            ToggleAclass() {
                
                document.getElementById("icon").classList.toggle("fa-times");
            }
    }
        
        
    }
</script>

<style scoped>
    .navbar-brand {
     width: 140px  
    }
    
    .nav-link:before {
        content: "";
        width: 100%;
        height: 2px;
        background-color: black;
        display: block;
        transform: translateY(27px);
        opacity: 0
    }
    .nav-link:hover:before {
        opacity: 1
    }
    #icon {
        font-size: 25px
    }
</style>