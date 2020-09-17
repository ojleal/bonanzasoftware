<template>
  <v-container fluid style="background-color: #f2f2f2;">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-8 align-items-center"
      style="background-color: #f2f2f2;"
    >
      <v-row align-content="center">
        <v-col cols="12">
          <div class="mx-auto text-center">
            <h1
              class="encabezado"
              style="font-size: 30px !important; font-weight: 700 !important; color: #d97c30 !important;"
            >
              <strong>UNSER TEAM</strong>
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
            src="../assets/mitarbeiter_gesucht.png"
            max-width="600px"
            max-height="400px"
            class="mx-auto"
          ></v-img>
        </v-col>
        <v-col cols="6" class="my-auto">
          <v-card
            outlined
            tile
            class="mx-auto mt-5 align-items-center"
            style="background-color: #f2f2f2;"
          >
            <div
              class="contenido"
              style="text-align: center !important; ; font-weight: 400; color: #666666 !important"
            >
              <h3
                style="text-align: center; font-size: 23px !important; color: #000000; font-weight: 400 !important;"
                class="mb-4"
              >Mitarbeiter gesucht</h3>
              <p
                style="text-align: center;"
              >Unser Produkt wächst stetig weiter und so soll auch unser Team weiterhin wachsen. An neuen Kollegen und Kolleginnen, Erfahrung und Wissen. Zur Zeit suchen wir Unterstützung in den folgenden Bereichen:</p>
              <p style="text-align: center;">
                Vertrieb
                <br />
                <span class="s1" style="color: #d97c30">
                  <strong>Vertriebsaußendienst für Deutschland</strong>&nbsp;
                  <strong>(w/m)</strong>
                </span>
              </p>
              <p style="text-align: center;">
                Entwicklung
                <br />
                <strong style="color: #d97c30">Developer PHP und Angular&nbsp;(w/m),&nbsp;</strong>
                <strong style="color: #d97c30">Front-End Development (w/m),&nbsp;</strong>
                <strong style="color: #d97c30">Webdesigner/in,&nbsp;</strong>
                <strong style="color: #d97c30">Projektmanagement IT (w/m)</strong>
              </p>
              <p class="p1" style="text-align: center;">
                <span
                  class="s1"
                >Falls wir Dein Interesse geweckt haben und Du Lust hast bei uns mitzuarbeiten (auch wenn Dich keine der genannten Positionen anspricht)</span>, freuen wir uns auf Deine Bewerbung.
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
  name: "section10",

  data() {
    return {};
  },
};
</script>