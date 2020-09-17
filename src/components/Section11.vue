<template>
  <v-container fluid style="background-color: #d5d5d5;">
    <v-container>
      <v-row align="center" align-content="center">
        <v-col cols="2">
          <v-img src="../assets/Logo.png" class="mx-auto" width="180" height="180"></v-img>
        </v-col>
        <v-col cols="3" class="my-auto" style="text-align: right">
          <v-btn color="#d97c30" style="color: #ffffff; font-size: 12px !important;" min-width="234" min-height="60">Beratungstermin vereinbaren</v-btn>
        </v-col>
        <v-col cols="3" class="my-auto" style="text-align: left">
          <v-btn color="#d97c30" style="color: #ffffff; font-size: 12px !important;" min-width="234" min-height="60">Prospekt anfordern</v-btn>
        </v-col>
        <v-col cols="4">
          <div class="my-auto text-justify">
            <p style="color: #d97c30; font-size: 15px">
              <strong>Wir beraten Sie gerne</strong>
            </p>
            <p style="font-size: 15px !important; font-weight: 400 !important">
              Mo - Fr: 10-18 Uhr
              <br />
              Phone: <a href="tel: +4922089162645" class="enlace">+49 2208 91 62 645</a>
              <br />
              Mail: <a href="mailto: info@bonanza-software.de" class="enlace">info@bonanza-software.de</a>
            </p>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </v-container>
</template>

<script>
export default {
  name: "section11",

  data() {
    return {};
  },
};
</script>