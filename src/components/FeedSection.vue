<template>
  <div class="mt-10">
    <v-layout>
      <v-flex>
        <div class="title">Latest Feed</div>
      </v-flex>
      <v-flex text-right>
        <v-btn icon>
          <v-icon>mdi-menu</v-icon>
        </v-btn>
        <v-btn color="#E7596F" icon>
          <v-icon>mdi-view-grid-outline</v-icon>
        </v-btn>
      </v-flex>
    </v-layout>
    <v-row class="mt-5">
      <v-col v-for="(image, i) in feedImages" :key="i">
        <v-card elevation="12" height="230" width="210" color="blue" class="mr-4">
          <v-img height="230" :src="image"></v-img>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      feedImages: [
        "https://images.unsplash.com/photo-1502429892517-ebe1510442a4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80",
        "https://images.unsplash.com/photo-1483728642387-6c3bdd6c93e5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1055&q=80",
        "https://images.unsplash.com/photo-1584701782235-beff0661e16a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=675&q=80",
        "https://images.unsplash.com/photo-1492056128351-09fb7a99969e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=562&q=80",
        "https://images.unsplash.com/photo-1495954484750-af469f2f9be5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80",
        "https://images.unsplash.com/photo-1515966097209-ec48f3216288?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80"
      ]
    };
  }
};
</script>

<style>
</style>