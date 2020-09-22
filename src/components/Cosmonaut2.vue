<template>
  <v-container fluid style="background-color: #f2f2f2;">
    <v-card flat tile color="transparent">
      <v-row>
        <v-col cols="10">
          <v-card
            class="mx-auto card_1 pa-5"
            max-width="850"
            min-height="250"
            raised
            rounded="xl"
            style="margin-top: -100px"
          >
            <v-list-item>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div
                  class="mb-1 text-center encabezado"
                  style="color: #d97c30 !important; font-size: 34px !important;"
                >DER CosmoNaut VON TRAFFICS</div>
                <v-divider class="pt-2 divisor" light></v-divider>
                <v-row align="center" justify="center">
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                  <v-icon small>star</v-icon>
                  <div class="mx-1"></div>
                  <v-icon color="#d97c30">fas fa-minus</v-icon>
                  <div class="mx-1"></div>
                </v-row>
                <v-divider class="pt-2 divisor" light></v-divider>
                <div class="mx-auto text-center" style="color: #666666; line-height: 1.5em;">
                  <p class="p1" style="text-align: center;">
                    <span>
                      <strong>Hotels</strong> – Veranstalterkontingente
                      <br />
                    </span>
                    <span>
                      <strong>Pauschalreisen</strong> – mehr als 160 Veranstalter
                      <br />
                    </span>
                    <span>
                      <strong>X-Angebote</strong> – mehr als 35 dynamische Anbieter
                      <br />
                    </span>
                    <span>
                      <strong>Flüge</strong> – Linienflüge, Charterflüge, Low Cost und Veranstalterkontingente
                      <br />
                    </span>
                    <span>
                      <strong>FeWo</strong> – weltweite Ferienhäuser und Ferienwohnungen
                      <br />
                    </span>
                    <span>
                      <strong>Kreuzfahrten</strong> – über CruiseA Kreuzfahrten von über 40 Reedereien
                      <br />
                    </span>
                    <span>
                      <strong>Mietwagenvergleich</strong> – mehrere Anbieter im Mietwagenvergleich
                      <br />
                    </span>
                    <span>
                      <strong>Versicherungsvergleich</strong> &nbsp;– mehrerer Reiseversicherer im Versicherungsvergleich
                      <br />
                    </span>
                    <span>
                      <strong>Parkplatzvergleich</strong> – Parkplätze an Abflughäfen vorab buchen
                      <br />
                    </span>
                    <span>
                      <strong>IRIS.plus</strong> – integrierte TUI IRIS.plus-Maske
                      <br />
                    </span>
                    <span>
                      <strong>HolidayCheck</strong> – integrierte Hotelbewertungen anzeigen und suchen
                    </span>
                  </p>
                </div>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col cols="12">
          <v-card class="mx-auto" max-width="1210" min-height="630" flat tile color="transparent">
            <div>
              <v-img src="../assets/cosmonaut_fenster.png" width="1210" height="630"></v-img>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "cosmonaut2",

  data() {
    return {};
  },
};
</script>