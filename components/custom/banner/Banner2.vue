<template>
  <div>
    <div class="banner2-component">
      <v-container>
        <!-- -----------------------------------------------
            Start Banner2
        ----------------------------------------------- -->
        <v-row justify="center" align="center">
          <v-col cols="12" md="6" class="d-flex align-center">
            <div class="text-center">
              <h2 class="banner2-title font-weight-bold">
                Preguntas frecuentes
              </h2>
              <p class="op-6 black--text">
                Resuelve tus dudas hasta el último detalle con las preguntas mas frecuentes.
              </p>
            </div>
          </v-col>
          <v-col cols="12" md="3">
            <v-img max-height="200" contain :src="require('@/static/FAQSimbolo.png')"></v-img>
          </v-col>
        </v-row>
        <v-row justify="center" align="center">
          <v-col cols="12" md="10">
            <v-expansion-panels flat >
              <v-expansion-panel class="transparent">
                <v-expansion-panel-header>¿La cuenta será completamente mia?</v-expansion-panel-header>
                <v-expansion-panel-content>
                  ¡Claro que si! La cuenta es totalmente suya después de haber finalizado su compra. Si por alguna razón no tiene acceso o presenta problemas al iniciar sesión en su cuenta comuníquese con el servicio de soporte.
                </v-expansion-panel-content>
              </v-expansion-panel>
              <v-expansion-panel class="transparent">
                <v-expansion-panel-header >¿Cuanto se demora en llegar mi cuenta?</v-expansion-panel-header>
                <v-expansion-panel-content>
                  La cuenta se entregará de manera inmediata, aunque sí se presentan fallas en el pago se puede demorar lo que tarde el banco en confirmar el trámite de pago.
                </v-expansion-panel-content>
              </v-expansion-panel>
              <v-expansion-panel class="transparent">
                <v-expansion-panel-header >¿Cuáles son los métodos de pago?</v-expansion-panel-header>
                <v-expansion-panel-content>
                  Se aceptan desde tarjetas de crédito, como transferencias bancarias como Nequi, Daviplata, etc.. y Paypal
                </v-expansion-panel-content>
              </v-expansion-panel>
            </v-expansion-panels>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Banner2
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Banner2",
  data() {
    return {};
  },
  methods: {},
};
</script>
