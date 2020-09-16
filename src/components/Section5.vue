<template>
  <v-container fluid style="background-color: #ffffff;">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto mt-5 align-items-center"
      style="background-color: #ffffff;"
    >
      <v-row align-content="center">
        <v-col cols="12">
          <div class="mx-auto text-center">
            <h1
              class="encabezado"
              style="font-size: 34px !important; font-weight: 400 !important; color: #d97c30 !important;"
            >UNSERE INTERNET-MARKETING PLATTFORM</h1>
          </div>
        </v-col>
      </v-row>
      <v-row align-content="center">
        <v-col class="mx-auto text-center" cols="12">
          <v-icon color="#d97c30" x-large>fas fa-minus</v-icon>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="8" class="my-auto">
          <v-img
            src="../assets/schaufenster.png"
            max-width="300px"
            max-height="200px"
            class="mx-auto"
          ></v-img>
        </v-col>
        <v-col cols="4">
          <v-card
            outlined
            tile
            class="mx-auto mt-5 align-items-center"
            style="background-color: #ffffff;"
          >
            <v-list-item tile>
              <div
                class="text-justify encabezado"
                style="font-weight: 400 !important; font-size: 30px !important;"
              >Ihr Auftritt im Internet</div>
            </v-list-item>
            <div class="contenido" style="text-align: justify !important; ; font-weight: 400;">
              <p>Die Lösung für Ihren Web/-Internetauftritt. Von einer Standard-Infoseite bis zu Ihrer Wunsch-IBE.</p>
              <p>Wählen Sie Ihr Lieblings-Design. Gestalten Sie die Website nach Ihren Wünschen. Füllen Sie die Angebotsfenster mit Ihren Angeboten.</p>
              <p>Moderne Touristik-Software auch für das WWW.</p>
            </div>
            <v-divider class="my-2 divisor" light></v-divider>
            <v-card-actions>
              <v-btn
                class="mx-auto btn_5"
                text
                style="min-width: 155px !important"
              >Mehr Informationen</v-btn>
            </v-card-actions>
            <v-divider class="my-4 divisor" light></v-divider>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "section5",

  data() {
    return {};
  },
};
</script>