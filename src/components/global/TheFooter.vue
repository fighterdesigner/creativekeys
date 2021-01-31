<template>
<footer class="container-fluid p-4">
    <div class="row justify-content-center p-3 text-center text-md-start">    
    <div class="col-12 col-md-6 col-lg-3 my-3">
        <h5>À propos</h5>
        <p>Qui somme nous?</p>
        <p>Developpeur</p>
    </div>
    <div class="col-12 col-md-6 col-lg-3 my-3">
        <h5>Services</h5>
        <p>Logiciels</p>
        <p>Solutions Web</p>
        <p>Réseaux et Système</p>
        <p>Assistance technique</p>
    </div>
    <div class="col-12 col-md-6 col-lg-3 my-3">
    <h5>Produits</h5>
        <p>Flex POS Point de vente</p>
        <p>Flex CS Gestion commerciale</p>
        <p>Flex PMS Système de gestion hôtelière</p>
        <p>Flex XM Solution ERP/GMAO</p>
        <p>Flex Paie</p>
    </div>
    <div class="col-12 col-md-6 col-lg-3 my-3">
    <h5>Revendeur</h5>
        <p>Telecharger</p>
    </div>
    </div>
    <div class="row text-center">
        <p class="col-12 col-md-4"><i class="fas fa-phone m-2"></i> (+212) 05 39 97 06 87</p>        
    <div class="col-12 col-md-4 social-media">
        <a target="_blank" href="https://www.facebook.com/creativekeys.ma/"><i class="fab fa-facebook m-2"></i></a>
        <a target="_blank" href="https://twitter.com/creativekeysma"><i class="fab fa-twitter m-2"></i></a>
        <a target="_blank" href="https://plus.google.com/u/0/+Soci%C3%A9t%C3%A9CREATIVEKEYS"><i class="fab fa-google m-2"></i></a>
        <a target="_blank" href="https://www.youtube.com/user/creativekeymaroc"><i class="fab fa-youtube m-2"></i></a>
    </div>
        <p class="col-12 col-md-4"><i class="fas fa-copyright m-2"></i>All rights reserved CreativeKeys</p>
    </div>    
</footer>
</template>

<script>
export default {
    name: "TheFooter"
} 
</script>

<style>
    footer {
        background-color:#e6e6e6;
        color: #616161
    }
    footer i {
        font-size: 20px;
        color: #616161
    }
    .social-media i:hover {
        color: #000
    }
    footer > div:first-child {
        margin-bottom: 40px
    }
</style>
