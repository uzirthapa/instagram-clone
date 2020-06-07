<template>
  <v-container class="pa-10">
    <stories-section />
    <feed-section />
  </v-container>
</template>

<script>
import StoriesSection from "../components/StoriesSection";
import FeedSection from "../components/FeedSection";
export default {
  components: {
    StoriesSection,
    FeedSection
  }
};
</script>

<style>
</style>