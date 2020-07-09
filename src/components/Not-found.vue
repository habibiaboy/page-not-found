<template>
  <v-container>
    <v-row>
      <v-col cols="12">
        <v-row justify="center">
          <v-col
            cols="12"
            md="6"
            sm="12"
          >
            <img class="img-404" src="../assets/img/Scarecrow.png"> 
          </v-col>

          <v-col
            cols="12"
            md="6"
            sm="12"
          >
            <h1 class="text-right-h1 ">I have bad news for you</h1>
            <p class="text-right-p">The page you are looking for might be removed or is temporarily unavailable</p>
            <v-btn large class="black white--text">BACK TO HOMEPAGE</v-btn>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'NotFound',
  }
</script>
