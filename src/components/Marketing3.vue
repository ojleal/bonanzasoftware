<template>
  <v-container fluid style="background-color: #ffffff;">
    <v-card flat tile color="transparent" style="margin-top: 100px">
      <v-row>
        <v-col cols="10">
          <v-card class="mx-auto" max-width="850" min-height="50" flat tile color="transparent">
            <div itemprop="text" style="line-height: 1.5em">
              <h3
                style="text-align: justify; font-size: 23px !important; color: #222222"
              >Präsentieren Sie Ihr Angebot</h3>
              <p style="font-size: 15px !important; color: #666666; text-align: justify; margin-top: 20px">
                Geben Sie Ihrer Website eine persönliche Note. Unser Design-Team steht Ihnen
                <br />dabei zur Seite und hilft all Ihre Wünsche in eine schöne Form zu gießen.
              </p>
            </div>
          </v-card>
        </v-col>
        <v-col cols="12">
          <v-card class="mx-auto" max-width="1200" min-height="630" flat tile color="transparent">
            <div>
              <v-img src="../assets/omp_designs_3.png" width="1210" height="630"></v-img>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "marketing3",

  data() {
    return {};
  },
};
</script>