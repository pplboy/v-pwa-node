<template>


  <div class="about">
    <h1>This is an about page</h1>
    <v-chip><router-link to="/about/aboutme">aboutme</router-link></v-chip>
    
    <v-chip><router-link to="/about/aboutour">aboutour</router-link></v-chip>
    

 <v-layout>
    <v-flex xs12 sm6 offset-sm3>
      <v-card>
        <v-img
          src="https://cdn.vuetifyjs.com/images/cards/desert.jpg"
          aspect-ratio="2.75"
        ></v-img>

        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">Kangaroo Valley Safari</h3>
            <div><router-view/></div>
          </div>
        </v-card-title>

        <v-card-actions>
          <v-btn flat color="orange">Share</v-btn>
          <v-btn flat color="orange">Explore</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>    
  </div>
</template>
