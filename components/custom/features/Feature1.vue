<template>
  <div>
    <div class="feature1-component">
        <!-- 
            Start Feature 1 Text
         -->
        <v-row justify="center">
          <v-col cols="12" md="10" lg="7">
            <div class="text-center mt-16">
              <h2 class="section-title font-weight-bold black--text">
                ¿Por qué trabajar con nosotros? 
              </h2>
              <p class="grey--text font-weight-regular">
                Follou.Co es una empresa dedicada al Marketing digital y la venta de cuentas con seguidores reales, para que las empresas o las personas que deseen expandir su marca o empezar a dar a conocer su contenido, lo hagan fácil y rápidamente. 
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- 
            End Feature 1 Text
        -->
        <!-- 
            Start Feature 1
       -->
        <v-row justify="center" class="mt-13">
          <v-col cols="12" md="4">
            <v-card elevation="0" class="transparent">
              <v-card-text>
                <v-img contain max-height="120" :src="require('@/static/AcompanamientoSimbolo.png')" class="mb-16"></v-img>
                <h5 class="font-weight-bold text-center  font-18 black--text">Acompañamiento constante</h5>
                <p class="mt-10 mb-8 text-center font-weight-regular">
                  Sabemos que el mundo del marketing digital es un lugar complejo, pero con nuestra ayuda nunca antes había sido tan fácil. A diferencia de otras paginas que tan solo venden seguidores, nosotros nos enfocamos en <span class="black--text">acompañar tu proceso </span> y guiarlo para que tu empresa pueda crecer.
                </p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card elevation="0" class="transparent">
              <v-card-text>
                <v-img contain max-height="120" :src="require('@/static/EstrellaDolar.png')" class="mb-16"></v-img>
                <h5 class="font-weight-bold text-center font-18 black--text">Impulsa tu Empresa</h5>
                <p class="mt-10 mb-8 text-center font-weight-regular">
                  Toda empresa confiable y creible debe tener una presencia en linea que impacte en su cliente. Con nuestros tips de <span class="black--text"> marketing digital</span>, y las cuentas con <span class="black--text">seguidores reales</span>, verás como tus ventas despegan rápidamente!
                </p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card elevation="0" class="transparent">
              <v-card-text>
                <v-img contain max-height="120" :src="require('@/static/MensajeSimbolo.png')" class="mb-16"></v-img>
                <h5 class="font-weight-bold text-center font-18 black--text">Comunicación Instantánea</h5>
                <p class="mt-10 mb-8 text-center font-weight-regular">
                  Sabemos que muchos servicios no están ahí para el cliente, afortunadamente no tienes porqué preocuparte de eso aquí. Follouco es una familia y tú eres parte de ella. Estamos <span class="black--text">conectados 24/7 </span> para resolver tus necesidades, preguntas, problemas o recibir comentarios.
                </p>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>

        <!-- 
            End Feature 1
        -->
    </div>
  </div>
</template>
<script>
export default {
  name: "Feature1",
  data() {
    return {};
  },
  methods: {},
};
</script>
