<template>
  <v-container fluid style="background-color: #84b5e2;">
    <v-container>
      <v-row>
        <v-col cols="8">
          <v-card color="#ffffff" rounded="lg" class="pa-8">
            <v-card-text style="text-align: center !important">
              <h2
                style="color: #d97c30 !important; font-size: 34px !important; font-weight: 700 !important;"
              >
                <strong>MIDOFFICE – LITTLE JOE</strong>
              </h2>
            </v-card-text>
            <v-divider class="pt-2 divisor" light></v-divider>
            <v-row align="center" justify="center">
              <v-icon color="#d97c30">fas fa-minus</v-icon>
              <div class="mx-1"></div>
              <v-icon small>star</v-icon>
              <div class="mx-1"></div>
              <v-icon color="#d97c30">fas fa-minus</v-icon>
              <div class="mx-1"></div>
            </v-row>
            <v-divider class="pt-2 divisor" light></v-divider>
            <div>
              <p style="text-align: center;">
                <span>Wie der Name es schon sagt. Joe ist unser Kleiner. Als „heranwachsender“ hat er natürlich nicht die Möglichkeiten/ Funktionen seiner großen Brüder.&nbsp;</span>
                <span>Noch etwas schüchtern kommt er auch nicht allein. Er darf nur in Begleitung raus…</span>
              </p>
              <p style="text-align: center;">
                <span>Bedeutet Joe wird nur im Paket, als Ergänzung zu unseren anderen Produkten oder bei Aktionen angeboten.</span>
              </p>
              <p style="text-align: center;">
                <span>Er verfügt über Basis Office Funktionen und hat auch das Traffics CRS kostenfrei integriert!&nbsp;</span>
                <span>Er ist sowohl bei den User Zugängen limitiert, als auch bei der</span>
                <span>An bindung weitere Module.</span>
              </p>
            </div>
          </v-card>
        </v-col>
        <v-col cols="4">
          <v-img src="../assets/stoerer_3.png" width="250" height="225"></v-img>
        </v-col>
      </v-row>
      <v-card flat tile color="transparent" class="mt-16">
        <v-row align="center" justify="center">
          <h2
            style="color: #ffffff !important; font-size: 30px !important; font-weight: 700 !important;"
          >
            <strong>DIE FUNKTIONEN</strong>
          </h2>
        </v-row>
        <v-row align="center" justify="center">
          <v-col cols="1">
            <v-divider style="border-color: #ffffff; border: 1px solid #ffffff"></v-divider>
          </v-col>
        </v-row>
        <v-row class="mx-auto">
          <v-col cols="4">
            <v-card
              class="mx-auto card_1"
              max-width="380"
              min-height="270"
              flat
              tile
              color="transparent"
            >
              <v-list-item three-line>
                <v-list-item-content>
                  <v-divider class="pt-5 divisor2" light></v-divider>
                  <v-row align="center" justify="center">
                    <v-icon x-large class="icono">fas fa-suitcase</v-icon>
                  </v-row>
                  <v-divider class="mt-4 divisor2" light></v-divider>
                  <div class="mx-auto text-center">
                    <h2 style="color: #1F7891; font-size: 23px !important;">Auftragsverwaltung</h2>
                    <v-divider class="mt-4 divisor2" light></v-divider>
                    <div class="contenido2" style="color:#ffffff;" itemprop="text">
                      <p style="text-align: center;">
                        – manuelle Erfassung für Aufträge
                        <br />– Unterscheidung zwischen Agenturinkasso und Direktinkasso
                        <br />– Erfassung von Kundenzahlungen
                        <br />– Detailmasken für die verschiedenen Leistungsarten
                        <br />– Zuordnung von einzelnen Teilnehmern zu einzelnen Leistungen
                        <br />– E-Mailversand und Druck von Anmeldung, Bestätigung und Rechnung
                      </p>
                    </div>
                  </div>
                </v-list-item-content>
              </v-list-item>
            </v-card>
          </v-col>
          <v-col cols="4">
            <v-card
              class="mx-auto card_1"
              max-width="380"
              min-height="270"
              flat
              tile
              color="transparent"
            >
              <v-list-item three-line>
                <v-list-item-content>
                  <v-divider class="pt-5 divisor2" light></v-divider>
                  <v-row align="center" justify="center">
                    <v-icon x-large class="icono">fas fa-user</v-icon>
                  </v-row>
                  <v-divider class="mt-4 divisor2" light></v-divider>
                  <div class="mx-auto text-center">
                    <h2 style="color: #009C41; font-size: 23px !important;">Kundenverwaltung / CRM</h2>
                    <v-divider class="mt-4 divisor2" light></v-divider>
                    <div class="contenido2" style="color:#ffffff; " itemprop="text">
                      <p style="text-align: center;">
                        – Kundenarten
                        <br />– Adressverwaltung (internationales Format)
                        <br />– beliebig viele Kontakte und Adressen pro Kunde
                        <br />– Hinterlegung der Standardkontaktart (E-Mail, Fax, Post)
                        <br />– zuordenbare Marketingkriterien
                        <br />– Selektion der Marketingkriterien
                        <br />– frei definierbare CRM Kriterien
                        <br />– Buchungshistorie
                        <br />– Belegverwaltung mit Nachdruckmöglichkeit
                        <br />– Kombination der Kriterien: Kunden, Buchungen und Marketing
                        <br />– Hinweis auf überfällige Termine
                      </p>
                    </div>
                  </div>
                </v-list-item-content>
              </v-list-item>
            </v-card>
          </v-col>
          <v-col cols="4">
            <v-card
              class="mx-auto card_1"
              max-width="380"
              min-height="270"
              flat
              tile
              color="transparent"
            >
              <v-list-item three-line>
                <v-list-item-content>
                  <v-divider class="pt-5 divisor2" light></v-divider>
                  <v-row align="center" justify="center">
                    <v-icon x-large class="icono">fas fa-archive</v-icon>
                  </v-row>
                  <v-divider class="mt-4 divisor2" light></v-divider>
                  <div class="mx-auto text-center">
                    <h2
                      style="color: #662575; font-size: 23px !important;"
                    >Stammdatenverwaltung, Setup und Konfiguration</h2>
                    <v-divider class="mt-4 divisor2" light></v-divider>
                    <div class="contenido2" style="color:#ffffff; " itemprop="text">
                      <p style="text-align: center;">
                        – vordefinierte Tabellen für 3 Letter Codes, Bankleitzahl, Postleitzahl
                        <br />– Veranstalterstamm (Daten, Ansprechpartner, Agenturnummern)
                        <br />– Kundenstammdaten, Anreden, Breifanreden, Titel, Kategorien
                        <br />– Vorbelegungen für Leistungsmasken, Zimmerarten, Zimmertypen, Versicherungen
                        <br />– Rabatte
                      </p>
                    </div>
                  </div>
                </v-list-item-content>
              </v-list-item>
            </v-card>
          </v-col>
        </v-row>
        <v-row class="mx-auto">
          <v-col cols="4">
            <v-card
              class="mx-auto card_1"
              max-width="380"
              min-height="270"
              flat
              tile
              color="transparent"
            >
              <v-list-item three-line>
                <v-list-item-content>
                  <v-divider class="pt-5 divisor2" light></v-divider>
                  <v-row align="center" justify="center">
                    <v-icon x-large class="icono">fas fa-shopping-cart</v-icon>
                  </v-row>
                  <v-divider class="mt-4 divisor2" light></v-divider>
                  <div class="mx-auto text-center">
                    <h2 style="color: #662575; font-size: 23px !important;">Kassenfunktionen</h2>
                    <v-divider class="mt-4 divisor2" light></v-divider>
                    <div class="contenido2" style="color:#ffffff; " itemprop="text">
                      <p style="text-align: center;">
                        – Einzahlungen an Bank
                        <br />– Zahlungen zu Aufträgen
                        <br />– Verwaltung von gemischten Zahlungsarten
                        <br />– Tagesabschluss
                        <br />– Kassenbuch
                        <br />– Kundenzahlungen
                        <br />– Zahlungskontrolle
                      </p>
                    </div>
                  </div>
                </v-list-item-content>
              </v-list-item>
            </v-card>
          </v-col>
          <v-col cols="4">
            <v-card
              class="mx-auto card_1"
              max-width="380"
              min-height="270"
              flat
              tile
              color="transparent"
            >
              <v-list-item three-line>
                <v-list-item-content>
                  <v-divider class="pt-5 divisor2" light></v-divider>
                  <v-row align="center" justify="center">
                    <v-icon x-large class="icono">fas fa-signal</v-icon>
                  </v-row>
                  <v-divider class="mt-4 divisor2" light></v-divider>
                  <div class="mx-auto text-center">
                    <h2 style="color: #662575; font-size: 23px !important;">Reporting</h2>
                    <v-divider class="mt-4 divisor2" light></v-divider>
                    <div class="contenido2" style="color:#ffffff; " itemprop="text">
                      <p style="text-align: center;">
                        – offene Posten Verwaltung je Debitor, An- und Restzahlungstermine, Mahnwesen
                        <br />– Statistiken und Auswertungen/Listen im Bereich von Reiseart, Zielgebiet, Beförderungsart
                        <br />– Ausgabe der Statistik als Tabellen-, Balken- oder Tortendiagramme
                        <br />– Buchungs-, Abreise- und Geburtstagslisten
                      </p>
                    </div>
                  </div>
                </v-list-item-content>
              </v-list-item>
            </v-card>
          </v-col>
        </v-row>
      </v-card>
    </v-container>
  </v-container>
</template>