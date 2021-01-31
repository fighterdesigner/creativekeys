<template>
<div class="PageNot py-5 text-center col-12 col-md-6 mx-auto">
    <h2>Page non trouvée</h2>
    <p>nous n'avons pas trouvé la page que vous recherchiez. veuillez retourner à la page d'accueil</p>
    <router-link to="/"><i class="fas fa-angle-left"></i>Page d'accueil</router-link>
</div>
</template>

<script>
export default {
    name: "PageNot"
}
</script>

<style>
    .PageNot a {
        background-color: #000;
        padding: 10px 20px;
        color: #fff;
        text-decoration: none
    }
    .PageNot a i {
        margin-right: 10px;
        transition: .3s
    }
    .PageNot a:hover i {
        transform: translateX(-8px);
    }
</style>
