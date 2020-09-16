<template>
  <v-container fluid style="background-color: #e2e2e2;">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto align-items-center"
      style="background-color: #e2e2e2;"
    >
      <v-row align-content="center">
        <v-col cols="12">
          <div class="mx-auto text-center">
            <h1
              class="encabezado"
              style="font-size: 34px !important; font-weight: 400 !important; color: #d97c30 !important;"
            >DER CosmoNaut VON TRAFFICS</h1>
          </div>
        </v-col>
      </v-row>
      <v-row align-content="center">
        <v-col class="mx-auto text-center" cols="12">
          <v-icon color="#d97c30" x-large>fas fa-minus</v-icon>
        </v-col>
      </v-row>
      <v-row>
        <v-card
          outlined
          tile
          class="mx-auto mt-2 align-items-center"
          style="background-color: #e2e2e2;"
        >
          <div class="mx-auto contenido" style="font-weight: 400 !important;">
            <p>Eins der renommiertesten Preisvergleich-Systeme komplett integriert!</p>
            <p>Hochwertig beraten, höhere Provisionen erzielen und zusätzlich Umsatz generieren.</p>
          </div>
          <v-divider class="my-2 divisor4" light></v-divider>
          <v-card-actions>
            <v-btn class="mx-auto btn_5" text style="min-width: 155px !important">Mehr Informationen</v-btn>
          </v-card-actions>
          <v-divider class="my-2 divisor4" light></v-divider>
        </v-card>
      </v-row>
      <v-row>
        <v-col cols="12" class="my-auto">
          <v-img
            src="../assets/cosmonaut_start_2.png"
            class="mx-auto"
          ></v-img>
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