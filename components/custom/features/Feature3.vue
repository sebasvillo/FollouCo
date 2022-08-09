<template>
  <div>
    <div class="feature3-component mini-spacer">
      <v-container class="position-relative">
        <!-- 
            Start Feature 3 Text
         -->
        <v-row class="hidden-md-and-down">
          <v-col cols="12" lg="10">
            <v-img
              :src="require('@/static/FollowerGain.png')"
              alt="feature"
              class="rounded"
            />
          </v-col>
          <v-col cols="12" md="7" lg="5" class="feature3-card">
            <v-card class="card-shadow">
              <v-card-text>
                <div class="pa-10 text-center">
                  <h3 class="feature3-title font-weight-medium">
                    Cuentas con seguidores reales!
                  </h3>
                  <p>
                    NO USAMOS BOTS, son ilegales, y reducen el alcance de tu cuenta. Nuestro servicio tiene como base la <span class="font-weight-bold"> garantía </span> de que tus seguidores sean 100% reales.
                  </p>
                  <v-btn
                    color="error"
                    class="btn-custom-lg linking mt-10 btn-arrow"
                    nuxt
                    large
                    @click="$vuetify.goTo(2640)"
                    elevation="0"
                  >
                    <span>¿Tienes Preguntas?</span>
                    <i class="mdi mdi-arrow-right"></i>
                  </v-btn>
                </div>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="hidden-lg-and-up" align="center" justify="center">
          <v-col cols="12" lg="10">
            <v-img
              :src="require('@/static/FollowerGain2.png')"
              alt="feature"
              class="rounded"
            />
          </v-col>
          <v-col cols="12" md="9" lg="5" class="">
            <v-card class="card-shadow">
              <v-card-text>
                <div class="pa-10 text-center">
                  <h3 class="feature3-title font-weight-medium mb-8">
                    ¡Cuentas con seguidores reales!
                  </h3>
                  <p>
                    Una de las prioridades de Follouco ha sido establecer una fórmula estable para conseguir seguidores reales. Actualmente no sirve de nada tener cuentas llenas de bots debido a las políticas de Instagram, es por ello que nuestro servicio tiene como base la <span class="font-weight-bold"> garantía </span> de que tus seguidores sean 100% reales.
                  </p>
                  <v-btn
                    color="error"
                    class="btn-custom-lg linking mt-10 btn-arrow"
                    nuxt
                    large
                    to="/"
                    @click="$vuetify.goTo(4440)"
                    elevation="0"
                  >
                    <span>¿Tienes Preguntas?</span>
                    <i class="mdi mdi-arrow-right"></i>
                  </v-btn>
                </div>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 3 Text
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Feature3",
  data() {
    return {};
  },
  methods: {},
};
</script>
