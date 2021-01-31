<template>
  <div class="container contactez-nous">
      
    <div class="contact-head py-5 mt-5 mb-0">
        <h2 class="text-center">Contactez nous</h2>
        <p class="h5 col-8 text-center my-4 mx-auto">Si vous avez des questions ou un problème, vous pouvez nous contacter ou visiter notre entreprise en utilisant la carte ci-dessous.</p>
    </div>  
    <iframe class="shadow mb-5" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6489.481164036274!2d-5.345709725224254!3d35.584794320867175!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd0b430d8e82be69%3A0x6820b3b886dfd128!2sCreativeKeys!5e0!3m2!1sfr!2s!4v1512145466962" frameborder="0" allowfullscreen=""></iframe>
    <div class="conatct-form">
        <form class="d-flex flex-column text-start">
            <div class="row col-12">
                <span class="col-12 col-md-4 d-flex flex-column my-2">
                    <label>Nom et Prénom:</label>
                    <input class="form-control" type="text" placeholder="Nom et Prénom...">
                </span>
                <span class="col-12 col-md-4 d-flex flex-column my-2">
                    <label>Email:</label>
                    <input class="form-control" type="email" placeholder="Email...">
                </span>
                <span class="col-12 col-md-4 d-flex flex-column my-2">
                    <label>Téléphone:</label>
                    <input class="form-control" type="numbers" placeholder="Téléphone...">
                </span>
                </div>
                <span class="col-12 my-4">
                    <label>Choisir votre produit:</label>
                    <select class="form-select" size="5" multiple aria-label="multiple select example">
                      <option value="1">Flex PMS Système de gestion hôtelière</option>
                      <option value="2">Flex CS Gestion commerciale</option>
                      <option value="3">Flex XM Solution ERP/GMAO</option>
                      <option value="4">Flex POS Point de vente</option>
                      <option value="5">Flex Paie</option>
                    </select>
                </span>
            <label>Votre Message:</label>
            <textarea class="form-control" placeholder="Votre Message..."></textarea>
            <button class="btn mt-2 text-light col-4 mb-5 mx-auto">Envoyer</button>
        </form>
    </div>

  </div>
</template>

<script>
export default {
    name: "ContactezNous",    
}
</script>

<style>
    iframe {
        width: 100%;
        height: 50vh;
        border-radius: 6px;
    }
    form textarea {
        min-height: 300px !important
    }
    form span {
        display: block;
        margin: 0 auto
    }
    form .btn {
        background-color: #000 !important;
    }
</style>
