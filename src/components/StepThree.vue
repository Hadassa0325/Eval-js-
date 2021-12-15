<template>
<h2> 3 Je sélectionne ma couleur </h2>
     

    <input type="radio" name="type" id="type1" class="type" >
    <label for="type"><p> Blanc </p>
    </label> <div class="BlocBlanc"> </div>
        
    <input type="radio" name="type" id="type2" class="type" >
    <label for="type">  <p> Noir </p> <div class="BlocNoir"> </div>
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

input {}

.BlocBlanc {
  background-color: white;
  border: black ;
  width: 50px;
  height: 50px;

}

.BlocNoir {
  background-color: rgb(0, 0, 0);
  border: black 5px ;
  width: 50px;
  height: 50px;

}

</style>