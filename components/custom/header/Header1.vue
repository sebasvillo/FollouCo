<template>
  <div>
    <!-- -----------------------------------------------
          Start Header
    ----------------------------------------------- -->
    <v-app-bar
      app
      class="app-header navbar-light header1 pb-12"
      flat
      hide-on-scroll
    >
      <v-container class="py-0 fill-height align-start mt-8">
        <!-- Logo -->
        <div class="logo mt-1">
          <NLink to="/">
            <v-img
              :src="require('@/static/FollouCoLogoCompleto2.png')"
              alt="logo"
              contain
              max-height="40"
              max-width="175"
            />
          </NLink>
        </div>

        <v-spacer></v-spacer>
        <!-- LG -->
        <div class="hidden-md-and-down">
          <div
            class="navigation mt-5"
            v-bind:class="[isActive ? 'd-block' : '']"
            @click="isActive = !isActive"
          >
            <v-btn text small @click="$vuetify.goTo(1280)" class="grey--text font-weight-bold">
              Nosotros
            </v-btn>
            <v-btn text small @click="$vuetify.goTo(1850)" class="grey--text font-weight-bold">
              Servicios
            </v-btn>
            <v-btn text small @click="$vuetify.goTo(2640)" class="grey--text font-weight-bold">
              Preguntas
            </v-btn>
            <v-btn text small @click="$vuetify.goTo(3000)" class="grey--text font-weight-bold">
              Contacto
            </v-btn>
          </div>
        </div>
        <!-- MD -->
        <div class="hidden-lg-and-up mt-5">
          <div
            class="navigation"
            v-bind:class="[isActive ? 'd-block' : '']"
            @click="isActive = !isActive"
          >
            <v-btn text small @click="$vuetify.goTo(2040)">
              Nosotros
            </v-btn>
            <v-btn text small @click="$vuetify.goTo(2780)">
              Servicios
            </v-btn>
            <v-btn text small @click="$vuetify.goTo(4300)">
              Preguntas
            </v-btn>
            <v-btn text small @click="$vuetify.goTo(4800)">
              Contacto
            </v-btn>
          </div>
        </div>
      </v-container>
    </v-app-bar>
    <!-- -----------------------------------------------
          End Header
    ----------------------------------------------- -->
  </div>
</template>

<script>
export default {
  name: "Header1",
  data() {
    return {
      isActive: false,
    };
  },
  methods: {
    toggleClass: function (event) {
      this.isActive = !this.isActive;
    },
  },
  computed: {

  },
};
</script>
