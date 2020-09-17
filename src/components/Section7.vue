<template>
  <v-container fluid style="background-color: #f2f2f2;">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-5 align-items-center"
      style="background-color: #f2f2f2;"
    >
      <v-row align-content="center">
        <v-col cols="12">
          <div class="mx-auto text-center">
            <h1
              class="encabezado mt-8"
              style="font-size: 30px !important; font-weight: 700 !important; color: #d97c30 !important;"
            >
              <strong>UNSER REISEMONITOR</strong>
            </h1>
          </div>
        </v-col>
      </v-row>
      <v-row align="center" justify="center" class="pb-4">
        <v-col cols="1">
          <v-divider style="border-color: #d97c30; border: 1px solid #d97c30"></v-divider>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="6" class="my-auto">
          <v-img
            src="../assets/schaufenster_2.png"
            max-width="600px"
            max-height="400px"
            class="mx-auto"
          ></v-img>
        </v-col>
        <v-col cols="6">
          <v-card
            outlined
            tile
            class="mx-auto mt-16 align-items-center"
            style="background-color: #f2f2f2;"
          >
            <div>
              <h3
                style="text-align: center; font-weight: 400 !important; font-size: 23px !important;"
              >Das digitale Schaufenster</h3>
              <p
                class="contenido"
                style="text-align: center; text-align: center !important; ; font-weight: 400; color: #666666 !important"
              >
                <span class="s1">
                  Lassen Sie Ihre Angebote leben!
                  <br />Präsentieren Sie in Ihrem
                </span>
                <span class="s2">Schaufenster</span>
                <span class="s1">
                  Live und in Farbe!
                  <br />Auch mit der Touristik-Software anderer Hersteller kombinierbar!
                  <br />
                </span>Durch intelligente Software sowohl für Reisebüros als auch für Reiseveranstalter bestens geeignet!
              </p>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "section7",

  data() {
    return {};
  },
};
</script>