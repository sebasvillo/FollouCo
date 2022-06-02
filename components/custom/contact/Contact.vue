<template>
  <div>
    <div>
      <v-img :src="require('@/static/ContactoFondo.png')">
        <!-- 
            Start Contact Form
        -->
        <v-row justify="center" align="center">
          <v-col cols="12" sm="10" md="12" lg="5">
            <h2 class="detail-title font-weight-medium white--text">
                Contáctanos!
            </h2>
            <v-btn  class="mr-12"
                    dark
                    large
                    color="#3fea51">
              <v-icon>mdi-whatsapp</v-icon>  Whatsapp
            </v-btn>
            <v-btn class="ml-12"
                    dark
                    large
                    color="#781b91">
              <v-icon>mdi-instagram</v-icon>  Instagram
            </v-btn>
          </v-col>
          <v-col cols="12" sm="10" md="12" lg="3">
            <div class="contact-detail-card">
              <p class="mt-15 op-8 mb-0 white--text">251 546 9442</p>
              <p class="op-8 mb-8 white--text">info@wrappixel.com</p>
              <p class="mt-15 op-8 mb-0 white--text">601 Sherwood Ave.</p>
              <p class="op-8 mb-0 white--text">San Bernandino, CA 92404</p>
            </div>
          </v-col>
        </v-row>
        <!-- 
            End Contact Form
        -->
      </v-img>
    </div>
  </div>
</template>
<script>
export default {
  name: "Contact",
  data() {
    return {
      name: "",
      email: "",
    };
  },
  methods: {},
};
</script>
