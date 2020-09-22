<template>
  <v-container fluid style="background-color: #f2f2f2;">
    <v-card flat tile color="transparent">
      <v-row>
        <v-col cols="10">
          <v-card class="mx-auto card_1 pa-5" max-width="850" min-height="250" raised rounded="xl" style="margin-top: -100px">
            <v-list-item>
              <v-list-item-content>
                <v-divider class="pt-5 divisor" light></v-divider>
                <div
                  class="mb-1 text-center encabezado"
                  style="color: #d97c30 !important; font-size: 34px !important;"
                >INTERNET-MARKETING PLATTFORM</div>
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
                  <p style="text-align: center;">
                    <span>Ob Sie nur tolle Bilder wirken lassen wollen oder Ihre eigenen Angebote umfangreich präsentieren möchten mit unserer Internet Marketing Plattform ist dies auch für Laien ganz einfach.</span>
                  </p>
                  <p
                    style="text-align: center;"
                  >Die Verknüpfung mit der Backoffice garantiert eine direkte Abwicklung der eingehenden Anfragen und Buchungen!</p>
                </div>
              </v-list-item-content>
            </v-list-item>
          </v-card>
        </v-col>
        <v-col cols="10">
          <v-card class="mx-auto" max-width="850" min-height="50" flat tile color="transparent">
            <div itemprop="text" style="color: #666666; text-align: justify;" class="mt-10">
              <h3 style="color: #222222; font-size: 23px !important;">Große Design-Auswahl</h3>
              <p style="color: #666666;" class="mt-4">
                Wählen Sie aus vielen verschiedenen Designs und gestalten Sie dieses ganz einfach mit
                <br />Ihren Farben und Ihrem Logo.
              </p>
            </div>
          </v-card>
        </v-col>
        <v-col cols="12">
          <v-card class="mx-auto" max-width="1200" min-height="630" flat tile color="transparent">
            <div>
              <v-img src="../assets/omp_designs_4.png" width="1210" height="630"></v-img>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "marketing2",

  data() {
    return {};
  },
};
</script>