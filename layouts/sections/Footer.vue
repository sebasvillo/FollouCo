<template>
  <!-- 
        Start Footer
   -->
  <v-img :src="require('@/static/ContactoFondo.png')" :height="imageHeight">
    <v-container>

      <v-row class="ml-4" justify="center" align="center">
        <!-- 
        First Column
       -->
        <v-col cols="12" sm="12" md="12" lg="6" class="px-xs-0">
          <h1 class="white--text mt-6">Estás a un click...</h1>
          <v-btn  class="mr-12 mt-4 mb-16"
                    light
                    large
                    color="#3fea51"
                    href="https://wa.me/573027381281?text=Hola.%20Me%20gustar%C3%ADa%20empezar%20mi%20proceso%20digital%20con%20Follou.Co!"
                    target="_blank"
                    width="200">
              <v-icon>mdi-whatsapp</v-icon>  Whatsapp
            </v-btn>
          <v-btn class="mt-4 mb-16"
                    light
                    large
                    color="#db93f0"
                    href="https://www.instagram.com/follouco/"
                    target="_blank"
                    width="200">
              <v-icon>mdi-instagram</v-icon>  Instagram
            </v-btn>
          <p class="white--text">
            Derechos Reservados por
            <a href="/" class="link py-16">follou.co</a>
          </p>
        </v-col>
        <!-- 
        Third Column
      -->
        <v-col cols="12" sm="12" md="12" lg="1" class="px-xs-0">
        </v-col>
        <!-- 
        Fourth Column
       -->
        <v-col cols="12" sm="12" md="12" lg="3" class="px-xs-0">
          <div class="">
            <h1 class="white--text">Contáctanos!</h1>
              <p class="mt-6 op-10 mb-0 white--text">+57 302 7381281</p>
              <p class="op-10 mb-16 white--text">follouco22@gmail.com</p>
            </div>
          <p class="white--text">Términos y Condiciones</p>
          <!-- <a href="/" class="link py-16">Términos y Condiciones</a> -->
        </v-col>
      </v-row>
    </v-container>
  </v-img>
  <!--
        End Footer
 -->
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      data: [],
    };
  },
  components: {
  },
  computed: {
    imageHeight () {
        switch (this.$vuetify.breakpoint.name) {
          case 'xs': return ('450') ; 
          case 'sm': return ('450') ; 
          case 'md': return ('450') ; 
          case 'lg': return ('230') ; 
          case 'xl': return ('230') ;
        }
    }
  }
};
</script>
 