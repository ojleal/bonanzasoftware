<template>
  <v-container fluid style="background-color: #84b5e2;">
    <v-card
      outlined
      tile
      width="1200"
      class="mx-auto align-items-center mt-8"
      style="background-color: #84b5e2;"
    >
      <v-row align-content="center">
        <v-col cols="12">
          <div class="mx-auto text-center">
            <h1
              class="encabezado"
              style="font-size: 30px !important; font-weight: 700 !important; color: #ffffff !important;"
            >UNSERE DIENSTLEISTUNGEN</h1>
          </div>
        </v-col>
      </v-row>
      <v-row align="center" justify="center" class="pb-4">
        <v-col cols="1">
          <v-divider style="border-color: #ffffff; border: 1px solid #ffffff"></v-divider>
        </v-col>
      </v-row>
      <v-row align-content="end">
        <v-col cols="12" class="my-auto">
          <v-img src="../assets/dienstleistungen.png" class="mx-auto"></v-img>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "section8",

  data() {
    return {};
  },
};
</script>