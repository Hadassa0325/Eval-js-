<template>

<h2> 2 J'indique mon type de rail </h2>
     

    <input type="radio" name="type" id="type1" class="type" >
    <label for="type"> <span> Modèle DS : Fixation au plafond pour rideaux légers </span> <br> <p> (sans doublure, hauteur max 300cm) </p>
    </label>
        
    <input type="radio" name="type" id="type2" class="type" >
    <label for="type"> <span> Modèle CS : Fixation au plafond ou au mur pour rideaux lourds </span> <br> <p> (doublé, hauteur + 300 cm) </p>
    </label>   

    <br>
    <button class="bouttonStep"
        type="button">
    Valider 
   </button>
    
</template>

<script>



</script>

<style  scoped>

/*.type {
    display: none;
}

.type + label {
   padding: 0.3rem 0.5rem;
   border: 1px solid  #ccc;
}

.type {
    display: none;
}

input[type="radio"].type:checked + label {
   border: 1px solid #000 ;
}
*/

</style>
