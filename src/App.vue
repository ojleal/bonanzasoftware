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
      <section7 />
      <section8 />
      <section9 />
      <section10 />
      <section11 />
      <footerpage />
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
import section7 from './components/Section7.vue'
import section8 from './components/Section8.vue'
import section9 from './components/Section9.vue'
import section10 from './components/Section10.vue'
import section11 from './components/Section11.vue'
import footerpage from './components/Footer.vue'

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
    section6,
    section7,
    section8,
    section9,
    section10,
    section11,
    footerpage
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
  color: #666666 !important;
}

.contenido2 {
  line-height: 1.5em !important;
  font-size: 15px !important;
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-weight: 400 !important;
  color: #ffffff !important;
}

p a {
  color: blue !important;
  text-decoration: none !important;
}

a.enlace:hover {
  text-decoration: underline !important;
}

.pie {
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 11px !important;
  font-weight: 400 !important;
  color: #ffffff !important;
}

.menu-footer {
  font-family: "Open Sans", "HelveticaNeue", "Helvetica Neue", Helvetica, Arial,
    sans-serif !important;
  font-size: 11px !important;
  font-weight: 400 !important;
  color: #ffffff !important;
  text-transform: capitalize;
}

.pie a {
  color: #ffffff !important;
  text-decoration: none;
}

a.menu-footer:hover {
  text-decoration: underline;
}
/* Css Temporal */
.wpml-ls-legacy-list-horizontal {
 border:1px solid transparent;
 padding:7px;
 clear:both
}
.wpml-ls-legacy-list-horizontal>ul {
 padding:0;
 margin:0 !important;
 list-style-type:none
}
.wpml-ls-legacy-list-horizontal .wpml-ls-item {
 padding:0;
 margin:0;
 list-style-type:none;
 display:inline-block
}
.wpml-ls-legacy-list-horizontal a {
 display:block;
 text-decoration:none;
 padding:5px 10px;
 line-height:1
}
.wpml-ls-legacy-list-horizontal a span {
 vertical-align:middle
}
.wpml-ls-legacy-list-horizontal .wpml-ls-flag {
 vertical-align:middle;
 width:18px;
 height:12px
}
.wpml-ls-legacy-list-horizontal .wpml-ls-flag+span {
 margin-left:.4em
}
.rtl .wpml-ls-legacy-list-horizontal .wpml-ls-flag+span {
 margin-left:0;
 margin-right:.4em
}

.wpml-ls-legacy-list-horizontal.wpml-ls-statics-footer>ul {
 text-align:center
}

.wpml-ls-item span {
  font-size: 12px !important;
}

.icono {
  font-size: 80px !important;
  color: #ffffff !important;
}

.p1 strong  {
  color: #d97c30;
  line-height: 1.5em;
}
</style>