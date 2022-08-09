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
          <v-dialog
                v-model="dialog"
                width="600px"
              >
                <template v-slot:activator="{ on, attrs }">
                  <a class="link py-16" @click.stop="dialog = true">Términos y Condiciones</a>
                </template>
                <v-card>
                  <v-card-title>
                    <span class="text-h5">Términos y Condiciones Follou.Co</span>
                  </v-card-title>
                  <v-card-text>


INFORMACIÓN RELEVANTE

 <v-spacer></v-spacer>

Es requisito necesario para la adquisición de los productos que se ofrecen en este sitio, que lea y acepte los siguientes Términos y Condiciones que a continuación se redactan. El uso de nuestros servicios, así como la compra de nuestros productos implicará que usted ha leído y aceptado los Términos y Condiciones de Uso en el presente documento. Todos nuestros productos van a ser adquiridos a través de una conversación automatizada mediante nuestra página de whatsapp. No es necesario acceder a una cuenta con contraseña de la página web para poder adquirir uno de nuestros servicios.

 <v-spacer></v-spacer>

Todas las compras y transacciones que se lleven a cabo por medio de este sitio web, están sujetas a un proceso de confirmación y verificación, el cual podría incluir la verificación del stock y disponibilidad de producto, validación de la forma de pago, validación de la factura (en caso de existir) y el cumplimiento de las condiciones requeridas por el medio de pago seleccionado.

 <v-spacer></v-spacer>

Los precios de los productos ofrecidos en esta Tienda Online están sujetos a cambios dependiendo de la oferta y demanda del momento, pero se mantiene constantes entre la página web y el servicio de la cuenta de whatsapp.

 <v-spacer></v-spacer>

LICENCIA

 <v-spacer></v-spacer>

Follouco a través de su sitio web concede una licencia para que los usuarios utilicen los productos que son vendidos en este sitio web de acuerdo a los Términos y Condiciones que se describen en este documento.

 <v-spacer></v-spacer>

USO NO AUTORIZADO

 <v-spacer></v-spacer>

En caso de que aplique (para venta de software, templetes, u otro producto de diseño y programación) usted no puede colocar uno de nuestros productos, modificado o sin modificar, en un CD, sitio web o ningún otro medio y ofrecerlos para la redistribución o la reventa de ningún tipo.

 <v-spacer></v-spacer>

PROPIEDAD

 <v-spacer></v-spacer>

Usted no puede declarar propiedad intelectual o exclusiva a ninguno de nuestros productos, modificado o sin modificar. Todos los productos son propiedad de los proveedores del contenido. En caso de que no se especifique lo contrario, nuestros productos se proporcionan sin ningún tipo de garantía, expresa o implícita. En ningún esta compañía será responsables de ningún daño incluyendo, pero no limitado a, daños directos, indirectos, especiales, fortuitos o consecuentes u otras pérdidas resultantes del uso o de la imposibilidad de utilizar nuestros productos.

 <v-spacer></v-spacer>

POLÍTICA DE REEMBOLSO Y GARANTÍA

 <v-spacer></v-spacer>

En el caso de productos que sean mercancías irrevocables no-tangibles, no realizamos reembolsos después de que se envíe el producto, usted tiene la responsabilidad de entender antes de comprarlo. Le pedimos que lea cuidadosamente antes de comprarlo. Hacemos solamente excepciones con esta regla cuando la descripción no se ajusta al producto. Hay algunos productos que pudieran tener garantía y posibilidad de reembolso, pero este será especificado al comprar el producto. En tales casos la garantía solo cubrirá fallas y sólo se hará efectiva cuando el producto se haya usado correctamente. Los términos de la garantía están asociados a fallas de fabricación y funcionamiento en condiciones normales de los productos y sólo se harán efectivos estos términos si el equipo ha sido usado correctamente. Esto incluye:

 <v-spacer></v-spacer>

– De acuerdo a las especificaciones técnicas indicadas para cada producto

 <v-spacer></v-spacer>

– En uso específico para la función con que fue diseñado

 <v-spacer></v-spacer>


COMPROBACIÓN ANTIFRAUDE

 <v-spacer></v-spacer>


La compra del cliente puede ser aplazada para la comprobación antifraude. También puede ser suspendida por más tiempo para una investigación más rigurosa, para evitar transacciones fraudulentas.

 <v-spacer></v-spacer>

PRIVACIDAD

 <v-spacer></v-spacer>

Este follou.co garantiza que la información personal que usted envía cuenta con la seguridad necesaria. Los datos ingresados por usuario o en el caso de requerir una validación de los pedidos no serán entregados a terceros, salvo que deba ser revelada en cumplimiento a una orden judicial o requerimientos legales.

 <v-spacer></v-spacer>

Follouco reserva los derechos de cambiar o de modificar estos términos sin previo aviso.

                  </v-card-text>
                </v-card>
              </v-dialog>
          <!--  -->
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
      dialog: false,
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
 