<template>
  <v-app-bar app color="#ffffff" dark elevate-on-scroll="true">
    <div class="d-flex align-center">
      <v-img
        alt="Bonanza Logo"
        class="shrink mr-2"
        contain
        src="../assets/logo_website.png"
        transition="scale-transition"
        width="200"
      />
    </div>

    <v-spacer></v-spacer>
    <div class="botones">
      <v-btn text rounded>Startseite</v-btn>
      <v-btn text rounded>Produkte</v-btn>
      <v-btn text rounded>Dienstleistungen</v-btn>
      <v-btn text rounded>Kontakt</v-btn>
      <v-btn
        text
        style="background: #d97c30; color: #ffffff !important;"
        class="botones2"
      >Beratungstermin</v-btn>
      <v-btn
        text
        style="background: #d97c30; color: #ffffff !important;"
        class="botones2"
      >Prospekt bestellen</v-btn>
    </div>
  </v-app-bar>
</template>

<script>
export default {
  name: "mainmenu",
  data() {
    return {};
  },
};
</script>
