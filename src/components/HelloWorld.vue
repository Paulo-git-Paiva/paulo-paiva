<template>
  <v-card class="mx-auto" color="grey-lighten-3">
    <v-layout>
      <v-app-bar 
        scroll-behavior="hide"
        color="teal-darken-4"
        image="https://picsum.photos/1920/1080?random"
      >
        <template v-slot:image>
          <v-img
            gradient="to top right, rgba(19,84,122,.8), rgba(128,208,199,.8)"
          ></v-img>
        </template>

        <v-app-bar-title>Title</v-app-bar-title>
        <v-row>
          <v-col>
            <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
          <span>Sombre mim</span>
          </v-btn>
          </v-col>
          <v-col>
            <v-btn icon>
          <v-icon>mdi-heart</v-icon>
          <span>Projetos</span>
        </v-btn>
          </v-col>
          <v-col>
            <v-btn icon>
          <v-icon>mdi-dots-vertical</v-icon>
        </v-btn>
          </v-col>
        </v-row>
      </v-app-bar>

      <v-main>
        <v-container fluid>
         
        </v-container>
      </v-main>
    </v-layout>
  </v-card>
</template>
<script setup>
  //
</script>
