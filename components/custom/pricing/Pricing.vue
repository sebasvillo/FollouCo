<template>
  <div>
    <div class="pricing-component mini-spacer">
      <v-container>
        <!-- 
            Start Pricing Text
         -->
        <v-row justify="center">
          <v-col cols="12" sm="10" md="9" lg="8">
            <div class="text-center">
              <h2 class="section-title font-weight-bold">
                Programas Hechos a tu Medida
              </h2>
              <p class="grey--text">Como cada empresa tiene distintas necesidades, realizamos un estudio para ofrecer un plan que se acomode a las necesidades de crecimiento y público. Por el bajo precio de <span class="text-weight-bold black--text"> 49.000 COP </span>, se presentará un estudio de acuerdo al plan que necesites. 
              </p>
            </div>
          </v-col>
        </v-row>

        <!--
            End Pricing Text
         -->
        <!-- 
            Start Pricing
        -->
        <v-row class="mt-13" justify="center">
          <v-col cols="12" md="8" lg="4">
            <v-card
              outlined
              elevation="0"
              class="pricing-card overflow-hidden mb-15 transparent"
            >
              <v-card-text class="text-center pa-15">
                <h5 class="font-weight-regular font-18">+5,000 seguidores</h5>
                <div>
                  <span class="price-text">Plata</span>
                </div>
                <div class="text-center black--text">
                  <p class="mt-16 pt-4">• Creación de Catálogo Web</p>
                  <p>• Diseño de Publicaciones</p>
                </div>
              </v-card-text>
              <v-btn
                block
                large
                depressed
                color="#b8127b"
                class="text-uppercase white--text rounded"
                href="https://wa.me/573027381281?text=Hola.%20Me%20gustar%C3%ADa%20empezar%20mi%20proceso%20digital%20con%20Follou.Co!"
                target="_blank"
              >
                Compra Ahora
              </v-btn>
            </v-card>
          </v-col>
          <v-col cols="12" md="8" lg="4">
            <v-card
              outlined
              elevation="0"
              class="pricing-card overflow-hidden mb-15 transparent"
            >
              <v-card-text class="text-center pa-15">
                <h5 class="font-weight-regular font-18">+10,000 seguidores</h5>
                <div>
                  <span class="price-text">Oro</span>
                  <p class="mb-n11">Todo lo de Plata +</p>
                </div>
                <div class="text-center black--text">
                  <p class="mt-16 pt-4">• Administración de Redes</p>
                  <p>• Creación de Página Web</p>
                </div>
              </v-card-text>
              <v-btn
                block
                large
                depressed
                color="#83249e"
                class="white--text text-uppercase rounded"
                href="https://wa.me/573027381281?text=Hola.%20Me%20gustar%C3%ADa%20empezar%20mi%20proceso%20digital%20con%20Follou.Co!"
                target="_blank"
              >
                Compra Ahora
              </v-btn>
            </v-card>
          </v-col>
          <v-col cols="12" md="8" lg="4">
            <v-card
              outlined
              elevation="0"
              class="pricing-card overflow-hidden mb-15 transparent"
            >
              <v-card-text class="text-center pa-15">
                <h5 class="font-weight-regular font-18">+30,000 seguidores</h5>
                <div>
                  <span class="price-text">Esmeralda</span>
                  <p class="mb-n11">Todo lo de Oro +</p>
                </div>
                <div class="text-center black--text">
                  <p class="mt-16 pt-4">• Creación de Bot de Whatsapp</p>
                  <p>• Publicidad con Influencers</p>
                </div>
              </v-card-text>
              <v-btn
                block
                large
                depressed
                color="#3d45c7"
                class="white--text text-uppercase rounded"
                href="https://wa.me/573027381281?text=Hola.%20Me%20gustar%C3%ADa%20empezar%20mi%20proceso%20digital%20con%20Follou.Co!"
                target="_blank"
              >
                Compra Ahora
              </v-btn>
            </v-card>
          </v-col>
        </v-row>

        <!--
            End Pricing
         -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Pricing",
  data() {
    return {};
  },
  methods: {},
};
</script>
