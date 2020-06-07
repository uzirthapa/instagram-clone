<template>
  <v-navigation-drawer color="grey lighten-5" floating class="pa-4" app permanent v-model="drawer">
    <v-layout class="pa-1">
      <div>
        <v-img
          width="130px"
          lazy-src="../assets/instagram_logo.png"
          src="../assets/instagram_logo.png"
        ></v-img>
      </div>
    </v-layout>
    <v-layout class="mt-10">
      <v-flex>
        <v-layout>
          <v-flex text-center>
            <!-- <v-card class="text-center" width="70" style="border-radius: 50%" outlined> -->
            <v-avatar class="outlined" size="80">
              <v-avatar size="70">
                <v-img
                  lazy-src="https://images.unsplash.com/photo-1554151228-14d9def656e4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=633&q=80"
                  src="https://images.unsplash.com/photo-1554151228-14d9def656e4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=633&q=80"
                />
              </v-avatar>
            </v-avatar>

            <!-- </v-card> -->

            <div class="mt-4 title">Emma Watson</div>
            <div class="mt-1 subtitle-2 grey--text">New York, NY</div>
            <div class="mt-5">
              <v-layout>
                <v-flex>
                  <div class="subtitle-2">Post</div>
                  <div class="subtitle-2 grey--text">116</div>
                </v-flex>
                <v-flex>
                  <div class="subtitle-2">Followers</div>
                  <div class="subtitle-2 grey--text">48m</div>
                </v-flex>
                <v-flex>
                  <div class="subtitle-2">Following</div>
                  <div class="subtitle-2 grey--text">48m</div>
                </v-flex>
              </v-layout>
            </div>
          </v-flex>
        </v-layout>
      </v-flex>
    </v-layout>
    <v-list nav dense class="mt-10">
      <v-list-item-group v-model="group" active-class="#E7596F--text">
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-home-outline</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Feed</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-compass-outline</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Explore</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-pound</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Trending</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-check-decagram</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Top Post</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-account-outline</v-icon>
          </v-list-item-icon>
          <v-list-item-title>People</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-bell-outline</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Notification</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-send-outline</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Direct</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-chart-pie</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Status</v-list-item-title>
        </v-list-item>
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-cog-outline</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Settings</v-list-item-title>
        </v-list-item>
      </v-list-item-group>
    </v-list>
  </v-navigation-drawer>
</template>

<script>
export default {};
</script>

<style>
.v-avatar.outlined {
  border: 2px solid #e7596f;
  background-color: transparent;
  border-radius: 50%;
  height: 100px;
  width: 100px;
}
</style>