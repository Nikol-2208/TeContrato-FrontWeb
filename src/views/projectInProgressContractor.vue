<template>
  <v-app>
    <v-row align="center" class="px-4 mx-5">
      <v-col cols="12" md="12" align="center">
        <h1>Projects in Progress</h1>
      </v-col>
      <v-col cols="8" md="4">
        <v-card
            class="mx-auto my-12"
            max-width="374"
        >
          <v-card-title>Kitchen Project</v-card-title>

          <v-card-text>
            <div>Small place .</div>
          </v-card-text>
          <v-img
              height="250"
              src="https://th.bing.com/th/id/OIP.axQ9WpnpbJ1fkxWF8mEZlgHaEv?pid=ImgDet&rs=1"
          ></v-img>
        </v-card>
        <v-container>
          <v-row dense>
            <v-col cols="12" align="center">
              <v-btn
                  color="primary"
                  elevation="2"
                  to="/controlMenuContractor"
              >To select</v-btn>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
      <v-col cols="8" md="4">
        <v-card
            class="mx-auto my-12"
            max-width="374"
        >
          <v-card-title>Living Room Project</v-card-title>

          <v-card-text>
            <div>Small place .</div>
          </v-card-text>
          <v-img
              height="250"
              src="https://i.pinimg.com/originals/44/ae/d7/44aed7832c1bbb39ece4f3c6eecd1219.jpg"
          ></v-img>
        </v-card>
        <v-container>
          <v-row dense>
            <v-col cols="12" align="center">
              <v-btn
                  color="primary"
                  elevation="2"
                  to="/controlMenuContractor"
              >To select</v-btn>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
      <v-col cols="8" md="4">
        <v-card
            class="mx-auto my-12"
            max-width="374"
        >
          <v-card-title>Backyard Project</v-card-title>

          <v-card-text>
            <div>Small place .</div>
          </v-card-text>
          <v-img
              height="250"
              src="https://i.pinimg.com/originals/88/c1/24/88c1245ba898f29fdc4e4bfe695e9ca2.jpg"
          ></v-img>
        </v-card>
        <v-container>
          <v-row dense>
            <v-col cols="12" align="center">
              <v-btn
                  color="primary"
                  elevation="2"
                  to="/controlMenuContractor"
              >To select</v-btn>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
      <v-container>
        <v-row dense>
          <v-col cols="12" align="center">
            <v-btn
                color="gray"
                elevation="2"
                to="/dashboard"
            >Back</v-btn>
          </v-col>
        </v-row>
      </v-container>
    </v-row>
    <navigation-bar></navigation-bar>
  </v-app>
</template>

<script>
import NavigationBar from "../components/navigation-bar";
export default {
  name: "projectInProgressContractor",
  components:{
    NavigationBar,
  },
}

</script>

<style scoped>

</style>
