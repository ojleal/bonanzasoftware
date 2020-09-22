<template>
  <v-container fluid style="background-color: #ffffff;">
    <v-card flat tile color="transparent" style="margin-top: 20px">
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
                style="text-align: center; font-size: 30px !important; line-height: 1.5em"
                class="pa-4"
              >
                <strong>UNSERE IBE</strong>
              </h2>
            </div>
            <v-col cols="3" class="mx-auto">
              <v-divider style="border-color: #d97c30; border: 1px solid #d97c30"></v-divider>
            </v-col>
            <div itemprop="text" style="color: #666666; font-size: 15px !important;">
              <div itemprop="text">
                <p
                  style="text-align: center;"
                >Gerne erläutern wir Ihnen unsere IBE Funktionalitäten.</p>
                <p
                  style="text-align: center;"
                >Besonders in Verbindung mit Ben ergibt sich hier ein großes Spektrum an Einsatzmöglichkeiten. Die Verknüpfung mit der Veranstalterlösung garantiert eine direkte Abwicklung der eingehenden Anfragen und Buchungen.</p>
                <p style="text-align: center;">Wir beraten Sie gerne!</p>
              </div>
            </div>
          </v-card>
        </v-col>
        <v-col>
          <v-btn
            class="mx-auto btn_1"
            text
            to="https://bonanza-software.de/termin-vereinbaren/"
          >Termin vereinbaren</v-btn>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "marketing5",

  data() {
    return {};
  },
};
</script>