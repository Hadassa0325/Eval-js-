<template>
  
    
    <h2> 1 J'indique mes dimensions </h2>

     <!--<p v-if="errors.length">
    <b>Please correct the following error(s):</b>
    <ul>
      <li v-for="error in errors">{{ error }}</li>
    </ul>
  </p>--> <!-- pour le message d'erreur -->

    <label for="dimensions"> Longueur du rail </label>
    <input type="number" id="dimensions" name="dimensions" placeholder="Min.0cm / max. 200 cm" min="0" max="200" >
    
    <br> <br>
    <button class="bouttonStep"
        type="button">
    Valider 
   </button>




</template>

<script>
/*export default {
  name: 'Etape',
  props: {
    error:"string"
    
  
  }
}*/ 
/*addEventlistener("submit", fonction() {
  alert("selectionner un element")
}); //si rien n'est selectionner mettre un message d'Alert */ 

</script>

<style lang="scss" scoped>

</style>