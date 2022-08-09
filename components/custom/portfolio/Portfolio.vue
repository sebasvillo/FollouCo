<template>
  <div>
    <div class="portfolio-component mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Portfolio
        ----------------------------------------------- -->
        <v-row class="mt-n16">
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img" @click="dialog_cuentas=true">
                <v-dialog
                    v-model="dialog_cuentas" width="600"
                  >
                    <template v-slot:activator="{ on, attrs }">
                      <img
                        :src="require('@/static/FollowersFondo.jpeg')"
                        class="img-fluid"
                        alt="portfolio"
                      />
                    </template>
                    <v-card width="600" color="#D62976">  
                      <v-card-title></v-card-title>
                      <v-spacer></v-spacer>
                      <v-container fluid>
                        <v-row justify="center">
                          <v-col cols="5" lg="3">
                            <v-btn
                              nuxt
                              dark
                              large
                              rounded
                              class="btn-custom-md"
                              href="https://wa.link/tlbzh8"
                              target="_blank"
                              depressed
                              color="#8f0fa1"
                              elevation="0"
                            >
                              ¡Lo Quiero!
                            </v-btn>
                          </v-col>
                        </v-row>
                      </v-container>
                      <v-card-text>
                        <v-img :src="require('@/static/CuentasCard.png')" contain max-height="480"></v-img>
                      </v-card-text>
                      
                    </v-card>
                  </v-dialog>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">
                  Cuentas con seguidores reales!
                </h5>
                <p class="font-14 mb-0">10.000 - 150.000 seguidores</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img" @click="dialog_catalogo=true">
                <v-dialog
                    v-model="dialog_catalogo" width="600"
                  >
                    <template v-slot:activator="{ on, attrs }">
                      <img
                        :src="require('@/static/Catalogo.png')"
                        class="img-fluid"
                        alt="portfolio"
                      />
                    </template>
                    <v-card width="600" color="#D62976">  
                      <v-card-title></v-card-title>
                      <v-spacer></v-spacer>
                      <v-container fluid>
                        <v-row justify="center">
                          <v-col cols="5" sm="3" >
                            <v-btn
                              nuxt
                              dark
                              large
                              rounded
                              class="btn-custom-md"
                              href="https://wa.link/khdygf"
                              target="_blank"
                              depressed
                              color="#8f0fa1"
                              elevation="0"
                            >
                              ¡Lo Quiero!
                            </v-btn>
                          </v-col>
                        </v-row>
                      </v-container>
                      <v-card-text>
                        <v-img :src="require('@/static/CatalogoInteractivoFoto.png')" contain max-height="480"></v-img>
                      </v-card-text>
                      
                    </v-card>
                  </v-dialog>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">
                  Catálogo interactivo con compras en línea
                </h5>
                <p class="font-14 mb-0"></p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img" @click="dialog_admin=true">
                <v-dialog
                    v-model="dialog_admin" width="600"
                  >
                    <template v-slot:activator="{ on, attrs }">
                      <img
                        :src="require('@/static/AdminRedesPortada.jpeg')"
                        class="img-fluid"
                        alt="portfolio"
                      />
                    </template>
                    <v-card width="600" color="#D62976">  
                      <v-card-title></v-card-title>
                      <v-spacer></v-spacer>
                      <v-card-text>
                        <v-img :src="require('@/static/AdminRedes.png')" contain max-height="480"></v-img>
                      </v-card-text>
                    </v-card>
                  </v-dialog>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">
                  Administración de redes
                </h5>
                <p class="font-14 mb-0">Incluida con cualquier compra</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img" @click="dialog_publicaciones=true">
                <v-dialog
                    v-model="dialog_publicaciones" width="600"
                  >
                    <template v-slot:activator="{ on, attrs }">
                      <img
                        :src="require('@/static/InstaPost.jpeg')"
                        class="img-fluid"
                        alt="portfolio"
                      />
                    </template>
                    <v-card width="600" color="#D62976">  
                      <v-card-title></v-card-title>
                      <v-spacer></v-spacer>
                      <v-container fluid>
                        <v-row justify="center">
                          <v-col cols="5" lg="3">
                            <v-btn
                              nuxt
                              dark
                              large
                              rounded
                              class="btn-custom-md"
                              href="https://wa.link/7l7rrh"
                              target="_blank"
                              depressed
                              color="#8f0fa1"
                              elevation="0"
                            >
                              ¡Lo Quiero!
                            </v-btn>
                          </v-col>
                        </v-row>
                      </v-container>
                      <v-card-text>
                        <v-img :src="require('@/static/PublicacionesFoto.png')" contain max-height="480"></v-img>
                      </v-card-text>
                      
                    </v-card>
                  </v-dialog>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">
                  Publicaciones
                </h5>
                <p class="font-14 mb-0">De 2 a 7 semanales</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img" @click="dialog_historias=true">
                <v-dialog
                    v-model="dialog_historias" width="600"
                  >
                    <template v-slot:activator="{ on, attrs }">
                      <img
                        :src="require('@/static/InstaStories.jpeg')"
                        class="img-fluid"
                        alt="portfolio"
                      />
                    </template>
                    <v-card width="600" color="#D62976">  
                      <v-card-title></v-card-title>
                      <v-spacer></v-spacer>
                      <v-container fluid>
                        <v-row justify="center">
                          <v-col cols="5" lg="3">
                            <v-btn
                              nuxt
                              dark
                              large
                              rounded
                              class="btn-custom-md"
                              href="https://wa.link/enzc3c"
                              target="_blank"
                              depressed
                              color="#8f0fa1"
                              elevation="0"
                            >
                              ¡Lo Quiero!
                            </v-btn>
                          </v-col>
                        </v-row>
                      </v-container>
                      <v-card-text>
                        <v-img :src="require('@/static/HistoriasFoto.png')" contain max-height="480"></v-img>
                      </v-card-text>
                    </v-card>
                  </v-dialog>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">
                  Historias
                </h5>
                <p class="font-14 mb-0">De 2 a 7 semanales</p>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6" lg="4">
            <v-card class="portfolio-card overflow-hidden">
              <div class="portfolio-img" @click="dialog_pgweb=true">
                <v-dialog
                    v-model="dialog_pgweb" width="600"
                  >
                    <template v-slot:activator="{ on, attrs }">
                      <img
                        :src="require('@/static/PgWebDesign.jpeg')"
                        class="img-fluid"
                        alt="portfolio"
                      />
                    </template>
                    <v-card width="600" color="#D62976">  
                      <v-card-title></v-card-title>
                      <v-spacer></v-spacer>
                      <v-container fluid>
                        <v-row justify="center">
                          <v-col cols="5" lg="3">
                            <v-btn
                              nuxt
                              dark
                              large
                              rounded
                              class="btn-custom-md"
                              href="https://wa.link/tzmcl8"
                              target="_blank"
                              depressed
                              color="#8f0fa1"
                              elevation="0"
                            >
                              ¡Lo Quiero!
                            </v-btn>
                          </v-col>
                        </v-row>
                      </v-container>
                      <v-card-text>
                        <v-img :src="require('@/static/PaginaWebFoto.png')" contain max-height="480"></v-img>
                      </v-card-text>
                    </v-card>
                  </v-dialog>
              </div>
              <v-card-text>
                <h5 class="font-weight-medium font-18">
                  Página Web
                </h5>
                <p class="font-12 mb-0">Para presentar a tu empresa de la mejor forma</p>
              </v-card-text>
            </v-card>
            </v-card>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Portfolio
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
<script>
export default {
  name: "Portfolio",
  data() {
    return {
      dialog_cuentas:false,
      dialog_catalogo:false,
      dialog_admin:false,
      dialog_publicaciones:false,
      dialog_historias:false,
      dialog_pgweb:false,
    };
  },
  methods: {},
};
</script>
