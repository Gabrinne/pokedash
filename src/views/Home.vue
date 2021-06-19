<template>
  <v-app class="indigo lighten-5">
    <v-container>
      <div class="d-flex justify-center">
        <v-img max-width="300px" src="../assets/img/logopokemon.png"></v-img>
      </div>
      <PokemonList />
    </v-container>
  </v-app>
</template>

<script>
import PokemonList from "../components/PokemonList.vue";

export default {
  name: "Home",
  components: {
    PokemonList,
  },
};
</script>
