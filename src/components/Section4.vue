<template>
  <v-container fluid style="background-color: #f2f2f2;">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-5 align-items-center"
      style="background-color: #f2f2f2;"
    >
      <v-row align="center" justify="center" class="pt-4 pb-2">
        <h2
          style="color: #d97c30 !important; font-size: 30px !important; font-weight: 700 !important;"
        >
          <strong>UNSERE OFFICE-SYSTEME</strong>
        </h2>
      </v-row>
      <v-row align="center" justify="center" class="pb-4">
        <v-col cols="1">
          <v-divider style="border-color: #d97c30; border: 1px solid #d97c30"></v-divider>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #d97c30 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado" style="color: #d97c30 !important;">LITTLE JOE</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img
                  src="../assets/little-joe.png"
                  aspect-ratio="1"
                  max-width="200px"
                  class="mx-auto"
                ></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Der simple Einstieg</h4>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Ihr Einstieg in das Mid-und BackOffice von Bonanza Software. Unsere Empfehlung für Kleinstreisebüros mit geringen Ansprüchen an die Funktionalität, die aber keine Abstriche bei der Qualität machen wollen. Ideal auch für Neugründer.</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-5 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_1" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #009c41 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado" style="color: #009c41 !important;">HOSS</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img src="../assets/hoss.png" aspect-ratio="1" max-width="200px" class="mx-auto"></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Viel Funktion bei höchster Qualität</h4>
                <v-divider class="my-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Kann alles! Nur Buchhaltung ist nicht sein Ding. Unsere Empfehlung für touristische Reisebüros, die ihre Buchhaltung ausgelagert haben. Durch verschiedene Module kann er sich jederzeit auf Ihre individuellen Bedürfnisse anpassen.</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-4 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_2" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #1f7891 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado" style="color: #1f7891 !important;">ADAM</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img src="../assets/adam.png" aspect-ratio="1" max-width="200px" class="mx-auto"></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Erfahren und immer einen Schritt voraus</h4>
                <v-divider class="my-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Die Version mit Buchhaltung. Ob Firmendienst, IATA Büro oder Leisure Travel – Adam kanns. Auch er passt sich auf Wunsch, durch verschiedene Zusatzmodule, noch näher an Ihre Bedürfnisse an. Das CRM hilft Ihnen bei der Kundenbindung.</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-4 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_3" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
        <v-col cols="3">
          <v-card
            class="mx-auto card_1"
            raised
            rounded-lg
            style="border: 3px solid #662575 !important;"
          >
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div class="mb-1 text-center encabezado" style="color: #662575 !important;">BEN</div>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-img src="../assets/ben.png" aspect-ratio="1" max-width="200px" class="mx-auto"></v-img>
                <v-divider class="my-4 divisor" light></v-divider>
                <h4 class="mb-4 text-center subtitulo">Die Veranstalter-Lösung</h4>
                <v-divider class="my-4 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                  >Die Möglichkeiten von Hoss oder Adam werden um die Veranstalter-Funktionalität erweitert. Ben ist die Lösung für alle Veranstalter. Ob Reisebüro mit Eigenveranstaltung, Spezialveranstalter oder der Neugründer.Ben hilft!</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="mt-5 divisor" :inset="inset"></v-divider>
            <v-card-actions>
              <v-btn class="mx-auto btn_4" text>Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-card class="mx-auto" max-width="100%" raised rounded-lg color="transparent" flat tile>
            <v-list-item three-line>
              <v-list-item-content>
                <v-divider class="pt-5 divisor3" light></v-divider>
                <div
                  class="mb-1 text-center encabezado"
                  style="color: #d97c30 !important; font-family: 'Open Sans' !important; font-weight:700 !important; font-size: 23px !important"
                >UNSER TRAFFICS CRS</div>
                <v-divider class="my-2 divisor3" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon>fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <v-divider class="my-2 divisor3" light></v-divider>
                <div class="mx-auto text-center">
                  <span
                    class="contenido"
                    style="color: #222222 !important; font-size: 18px !important"
                  >In all unseren Office-Systemen ist das Traffics CRS System kostenfrei integriert!</span>
                </div>
              </v-list-item-content>
            </v-list-item>
            <v-divider class="my-2 divisor3" light></v-divider>
            <v-card-actions>
              <v-btn
                class="mx-auto btn_5"
                text
                style="min-width: 155px !important"
              >Mehr Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-2 divisor3" light></v-divider>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "section4",

  data() {
    return {};
  },
};
</script>