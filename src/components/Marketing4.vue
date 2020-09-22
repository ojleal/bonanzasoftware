<template>
  <v-container fluid style="background-color: #f2f2f2;">
    <v-card flat tile color="transparent" style="margin-top: 100px">
      <v-row>
        <v-col cols="12">
          <v-card
            class="mx-auto pa-5"
            max-width="570"
            min-height="50"
            flat
            tile
            color="transparent"
          >
            <div style="color:#d97c30; " itemprop="text">
              <h2
                style="text-align: center; font-size: 30px !important; line-height: 1.5em; font-weight: 700 !important;"
                class="pa-4"
              >
                <strong>UNSERE ANGEBOTSFENSTER UND BUCHUNGSSTRECKE</strong>
              </h2>
            </div>
            <v-col cols="3" class="mx-auto">
              <v-divider style="border-color: #d97c30; border: 1px solid #d97c30"></v-divider>
            </v-col>
            <div itemprop="text" style="color: #666666; font-size: 15px !important;">
              <p
                style="text-align: center;"
              >Wir bieten Ihnen die gesamte Buchungsstrecke. Von der Erstellung eigener Angebote bis zur Buchung und Kontingentabfrage alles in einer Software.</p>
              <p
                style="text-align: center;"
              >Sie können Ihre aktuellen Angebote direkt in die Angebotsfenster auf Ihrer Website eintragen.</p>
            </div>
          </v-card>
        </v-col>
        <v-col cols="12">
          <v-card class="mx-auto" max-width="1200" min-height="630" flat tile color="transparent">
            <div>
              <v-img src="../assets/buchungsstrecke_2.png" width="1210" height="630"></v-img>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "marketing4",

  data() {
    return {};
  },
};
</script>