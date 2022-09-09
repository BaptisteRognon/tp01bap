<template >
     <div class="p-2">
        <h2>Page simple</h2>
        <card image="/une.jpg"/>
     </div>
  </template>

<script setup lang="ts">
    
    import card from "../components/card.vue";
    
  const props = defineProps({
    foo:String
  });

  const unObjet0 = { nom:"une card de maison",
  prix: 45,
  favori: false,
  image: "./une.jpg", 
  nbr500: "number",}
  const unObjet1 = {nom:"card",
  prix: "number",
  favori: "Donlman",
  image: "./une.jpg",
  nbr500: "number",}
  
  </script>
