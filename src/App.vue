<template>
  <v-app>
    <v-main>
      <mainmenu />
      <phoneinfo />
      <section1 />
      <section2 />
      <section3 />
      <section4 />
      <section5 />
      <section6 />
    </v-main>
  </v-app>
</template>

<script>
import mainmenu from './components/Mainmenu.vue'
import phoneinfo from './components/Phoneinfo.vue'
import section1 from './components/Section1.vue'
import section2 from './components/Section2.vue'
import section3 from './components/Section3.vue'
import section4 from './components/Section4.vue'
import section5 from './components/Section5.vue'
import section6 from './components/Section6.vue'

export default {
  name: 'App',
  components: {
    mainmenu,
    phoneinfo,
    section1,
    section2,
    section3,
    section4,
    section5,
    section6
  }
}
</script>

<style>
#app {
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.botones .v-btn {
  color: #61615f !important;
  font-size: 13px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 600 !important;
  text-transform: capitalize !important;
  padding-top: 0px !important;
  padding-right: 8px !important;
  padding-bottom: 0px !important;
  padding-left: 8px !important;
}

.v-btn.botones2 {
  width: 140px;
  padding-right: 16px !important;
  padding-left: 16px !important;
  margin-right: 5px !important;
}

.v-btn {
  letter-spacing: 0px !important;
  line-height: 88px !important;
}

.v-btn.botones2 :hover {
  text-decoration: none;
}

.botones.v-btn :hover {
  background-color: #cde0e7;
}

.contenedor {
  height: 30px;
  background-color: #d97c30;
}

.contenedor span {
  background-color: #d97c30; 
  color: #ffffff !important;
  font-size: 11px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial, sans-serif !important;
  font-weight: 700 !important;
  text-transform: capitalize !important;
}

.contenedor span a {
  color: blue;
  text-decoration: none;
}

span :hover {
  text-decoration: underline !important;
}
.btn_1 {
  background-color: #d97c30;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
  min-width: 120px !important;
}

.btn_2 {
  background-color: #009c41;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
  min-width: 120px !important;
}

.btn_3 {
  background-color: #1f7891;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
  min-width: 120px !important;
}

.btn_4 {
  background-color: #662575;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
  min-width: 120px !important;
}

.btn_5 {
  background-color: #d97c30;
  color: #ffffff !important;
  text-transform: capitalize !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 13px !important;
  min-width: 120px !important;
}

.subtitulo {
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 18px !important;
  text-transform: capitalize !important;
  font-weight: 400 !important;
}

.group {
  display: flex;
  flex: 1;
  justify-content: space-around;
}

.divisor {
  border-color: #ffffff !important;
}

.divisor2 {
  border-color: #84b5e2 !important;
}

.divisor3 {
  border-color: #f2f2f2 !important;
}

.divisor4 {
  border-color: #e2e2e2 !important;
}

.v-sheet.v-card {
  border-radius: 10px !important;
  border: none;
}

.card_1 {
  max-width: 280;
  min-height: 670;
}

.encabezado {
  font-size: 23px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 700 !important;
}

.contenido {
  line-height: 1.5em !important;
  font-size: 15px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 400 !important;
}
</style>