<template>
  <div>
    <v-layout>
      <v-flex>
        <div class="title">Featured Stories</div>
      </v-flex>
      <v-flex text-right>
        <v-btn depressed class="text-none" color="grey lighten-4">
          <span class="grey--text">Popular Stories</span>
        </v-btn>
      </v-flex>
    </v-layout>
    <v-layout justify-start class="mt-7">
      <v-card elevation="12" height="230" width="170" color="blue" class="mr-4">
        <v-img
          height="230"
          src="https://images.unsplash.com/photo-1525138079-9424be9df411?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=675&q=80"
        ></v-img>
      </v-card>
      <v-card elevation="12" height="230" width="170" color="blue" class="mr-4">
        <v-img
          height="230"
          src="https://images.unsplash.com/photo-1523224949444-170258978eef?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=564&q=80"
        ></v-img>
      </v-card>
      <v-card elevation="12" height="230" width="170" color="blue" class="mr-4">
        <v-img
          height="230"
          src="https://images.unsplash.com/photo-1551818633-579bccc6210c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1267&q=80"
        ></v-img>
      </v-card>
      <v-card elevation="12" height="230" width="170" color="blue" class="mr-4">
        <v-img
          height="230"
          src="https://images.unsplash.com/photo-1478296046035-d4fc77bec472?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=634&q=80"
        ></v-img>
      </v-card>
    </v-layout>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>