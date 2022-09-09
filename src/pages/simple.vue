<template >
     <section>
    <h1 class="text-2xl">
      Bonjour<code class="font-mono text-base">/src/pages/index.vue</code>
    </h1>
  </section>
  </template>

<script>
    import card from "./components";
  
    
    export default {
      props: {
        location: String,
        adress: String,
        price: Number,
        favori: Boolean,
        image: String,
        nbrbath: Number,
        nbrbed: Number,
        size: String
      },
      components: { card },
    };
    </script>