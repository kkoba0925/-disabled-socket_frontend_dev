<template>
  <v-row>
    <v-col cols="8">
      <v-toolbar
        color="green darken-1"
        class="pa-4 my-4"
      ></v-toolbar>
      <v-card
        v-for="n in 20"
        :key="n"
        class="py-1 px-2 my-4"
        color="grey lighten-5"
        align="center"
      >
      
      <v-row>

        <v-col cols="1" class="my-auto">
          <v-btn 
            class="my-auto"
            color="success" 
            fab
            outlined
            x-small
            left
          ></v-btn>
        </v-col>

        <v-col cols="10" class="py-3">
          <v-card-title 
            class="text-h5 py-1"
          >
            task
          </v-card-title>

          <v-divider></v-divider>

          <v-card-subtitle
            class="py-1 px-1 ml-1 float-left"
          >
            subtext
          </v-card-subtitle>
          <v-card-subtitle
            class="py-1 px-1 ml-1 float-left"
          >
            subtext
          </v-card-subtitle>
        </v-col>

        <v-col cols="1" class="my-auto">
          <v-btn 
            class="my-auto"
            color="purple darken-1"
            fab
            outlined
            x-small
            right
          ></v-btn>
        </v-col>

      </v-row>
      

      </v-card>
    </v-col>

    <v-col cols="4">
      submenu
    </v-col>

  </v-row>
</template>