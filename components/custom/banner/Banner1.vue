<template>
  <div>
    <v-img :src="require('@/static/Fondo.png')" :height="imageHeight">
      <v-container>
          <v-row justify="center" align="center" class="hidden-md-and-down">
            <v-col cols="12" md="1" lg="6" class="d-flex">
              <div class="text-left">
                <v-img :src="require('@/static/InstaPalabra1.png')" contain width="500" class="mb-10"></v-img>
                <v-img :src="require('@/static/MuchoMasFacil.png')" contain width="500" class="mb-10"></v-img>
                <p class="op-8 font-weight-regular">
                  FollouCo te trae estrategias de marketing digital y cuentas de instagram con seguidores reales, que simplificarán tu lucha por seguidores, brindarán mayores ventas a tu empresa, y le darán credibilidad a tu página. Perfecto para emprendimientos, negocios o cualquiera que no se quiera quedar atrás en el mercado digital. 
                </p>
                <div class="mt-16 pt-2 white--text">
                  <v-btn
                    nuxt
                    dark
                    large
                    rounded
                    class="btn-custom-md"
                    @click="$vuetify.goTo(3000)"
                    depressed
                    color="#8f0fa1"
                    elevation="0"
                  >
                    Contáctanos!
                  </v-btn>
                </div>
              </div>
            </v-col>
            <v-col align="end" cols="12" lg="6" class="mt-16" >
              <v-img
                :src="require('@/static/Cohete.png')"
                alt="banner"
              />
            </v-col>
          </v-row>
          <v-row justify="center" align="end" class="hidden-lg-and-up">
            <v-col cols="12">
              <div class="text-center">
                <v-img :src="require('@/static/InstaPalabra1.png')" contain width="650" class="mb-10" ></v-img>
                <v-img :src="require('@/static/MuchoMasFacil.png')" contain width="650" class="mb-10" ></v-img>
                <p class="op-8 font-weight-regular ">
                  FollouCo te trae estrategias de marketing digital y cuentas de instagram con seguidores reales, que simplificarán tu lucha por seguidores, brindarán mayores ventas a tu empresa, y le darán credibilidad a tu página. Perfecto para emprendimientos, negocios o cualquiera que no se quiera quedar atrás en el mercado digital. 
                </p>
                <div class="mt-16 pt-2 white--text">
                  <v-btn
                    nuxt
                    dark
                    large
                    rounded
                    @click="$vuetify.goTo(4800)"
                    class="btn-custom-md"
                    depressed
                    color="#8f0fa1"
                    elevation="0"
                  >
                    Contáctanos!
                  </v-btn>
                </div>
              </div>
            </v-col>
            <v-col justify="center" align="center" cols="12" class="mt-10" >
              <v-img
                :src="require('@/static/Cohete.png')"
                alt="banner"
                contain
                max-width="500"
              />
            </v-col>
          </v-row>
        <!-- 
            End Banner1
        -->
      </v-container>
    </v-img>
  </div>
</template>
<script>
export default {
  name: "Banner1",
  data() {
    return {
    };
  },
  methods: {
    },
  computed: {
    imageHeight () {
        switch (this.$vuetify.breakpoint.name) {
          case 'xs': return ('970') ; 
          case 'sm': return ('1000') ; 
          case 'md': return ('1040') ; 
          case 'lg': return ('530') ; 
          case 'xl': return ('530') ;
        }
    }
  }
};
</script>
