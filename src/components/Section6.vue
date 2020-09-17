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
          <div class="mx-auto text-center mt-8 mb-3">
            <h2
              class="encabezado"
              style="font-size: 30px !important; font-weight: 700 !important; color: #d97c30 !important;"
            >DER CosmoNaut VON TRAFFICS</h2>
          </div>
        </v-col>
      </v-row>
      <v-row align="center" justify="center" class="pb-4">
        <v-col cols="1">
          <v-divider style="border-color: #d97c30; border: 1px solid #d97c30"></v-divider>
        </v-col>
      </v-row>
      <v-row>
        <v-card
          outlined
          tile
          class="mx-auto align-items-center"
          style="background-color: #e2e2e2;"
        >
          <div class="mx-auto contenido" style="font-weight: 400 !important; line-height: 1.5em !important;">
            <p>
              Eins der renommiertesten Preisvergleich-Systeme komplett integriert!
              <br />
              <span>Hochwertig beraten, höhere Provisionen erzielen und zusätzlich Umsatz generieren.</span>
            </p>
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
          <v-img src="../assets/cosmonaut_start_2.png" class="mx-auto"></v-img>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "section6",

  data() {
    return {};
  },
};
</script>