<template>
  <v-footer color="#d97c30" height="70px" padless>
    <v-row justify="center" no-gutters>
      <v-col class="my-auto text-center" cols="4" style="margin-top: 20px !important;">
        <p class="pie">
          © Bonanza Software GmbH 2018 - {{ new Date().getFullYear() }} | Powered by
          <a
            href="https://itexon.com"
            target="blank"
            class="menu-footer"
          >Itexon GmbH</a>
        </p>
      </v-col>
      <v-col class="my-auto text-center" cols="4">
        <div
          class="wpml-ls-statics-footer wpml-ls wpml-ls-legacy-list-horizontal"
          id="lang_sel_footer"
        >
          <ul>
            <li
              class="wpml-ls-item"
            >
              <a href="https://bonanza-software.de" class="wpml-ls-link">
                <img
                  class="wpml-ls-flag"
                  src="../assets/de-flag.png"
                  alt="de"
                  title="Deutsch"
                />
                <span class="wpml-ls-native icl_lang_sel_native">Deutsch</span>
              </a>
            </li>
            <li
              class="wpml-ls-item"
            >
              <a href="https://bonanza-software.de/?lang=fr" class="wpml-ls-link">
                <img
                  class="wpml-ls-flag"
                  src="../assets/fr-flag.png"
                  alt="fr"
                  title="Français"
                />
                <span class="wpml-ls-native icl_lang_sel_native">Français</span>
              </a>
            </li>
            <li
              class="wpml-ls-item"
            >
              <a href="https://bonanza-software.de/?lang=en" class="wpml-ls-link">
                <img
                  class="wpml-ls-flag"
                  src="../assets/en-flag.png"
                  alt="en"
                  title="English"
                />
                <span class="wpml-ls-native icl_lang_sel_native">English</span>
              </a>
            </li>
            <li
              class="wpml-ls-item"
            >
              <a href="https://bonanza-software.de/?lang=nl" class="wpml-ls-link">
                <img
                  class="wpml-ls-flag"
                  src="../assets/nl-flag.png"
                  alt="nl"
                  title="Nederlands"
                />
                <span class="wpml-ls-native icl_lang_sel_native">Nederlands</span>
              </a>
            </li>
          </ul>
        </div>
      </v-col>
      <v-col class="my-auto text-center" cols="4">
        <v-btn
          v-for="link in links"
          :key="link"
          color="#d97c30"
          text
          rounded
          class="menu-footer"
          style="padding-left: 4px; padding-right: 4px;"
        >{{ link }}</v-btn>
      </v-col>
    </v-row>
  </v-footer>
</template>


<script>
export default {
  name: "footerpage",

  data: () => ({
    links: ["Kontakt", "Impressum", "Datenschutz", "AGB"],
    lang: ["Deutsch", "Français", "English", "Nederlands"],
  }),
};
</script>