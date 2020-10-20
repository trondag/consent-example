<template>
  <v-container>
    <v-row>
      <v-col cols="12">
      </v-col>

      <v-col class="mb-4">
          <h3 class="mb-2">Vår behandling av dine opplysninger</h3>
        <v-expansion-panels>
          <v-expansion-panel>

          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
                <v-icon color="blue">mdi-account-arrow-right</v-icon> Personopplysninger vi samler inn<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>
              Vi samler vi inn følgende informasjon om deg:
              <div class="ma-2">
                <v-chip class="ma-2" label text-color="white" color="green"><v-icon>mdi-clipboard-account</v-icon>Navn</v-chip>
                <v-chip class="ma-2" label text-color="white" color="pink"><v-icon>mdi-at</v-icon>Epostadresse</v-chip>
                <v-chip class="ma-2" label text-color="white" color="purple"><v-icon>mdi-ip-network</v-icon>IP-adresse</v-chip>
                <v-chip class="ma-2" label text-color="white" color="blue"><v-icon>mdi-map-marker-path</v-icon>Hvordan du beveger deg rundt på vårt websted</v-chip>
                </div>
              <v-expansion-panels>                
              <v-expansion-panel>
                <v-expansion-panel-header>Mer informasjon</v-expansion-panel-header>
                <v-expansion-panel-content>
                  <b>Navn</b>
                  <p>Navnet ditt samles inn dersom du registrerer en brukerkonto i vårt system. Navnet ditt lagres på en database i England og en i USA. AWS er selskapet som databasene ligger hos.</p>
                  <br>
                  <b>Epostadresse</b>
                  <p>
                    Epostadressen din samles inn dersom du registrerer en brukerkonto i vårt system eller melder deg på nyhetsbrev. Eposten lagres på en database i England og en i USA. AWS er selskapet som databasene ligger hos
                  </p>
                  <br>
                  <b>IP-adresse</b>
                  <p>
                    IP-adressen din lagres dersom du samtykker til det i dialogboksen som dukker opp med en gang du besøker vårt nettsted første gang.
                    Adressen blir lagret to databaser, en i England og en i USA. AWS er selskapet disse databasene ligger hos.
                  </p>
                </v-expansion-panel-content>
              </v-expansion-panel>
              </v-expansion-panels>
            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-reactivate</v-icon> Hvordan vi bruker personopplysningene<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-group</v-icon> Hvordan vi deler dine personopplysninger med andre parter<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-switch</v-icon> Hvilke parter deler hvilke personopplysninger med oss?<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
        </v-expansion-panels>
          <h3 class="mb-2 mt-2">Dine rettigheter</h3>
        <v-expansion-panels>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-details</v-icon> Hvordan eksportere personopplysninger?<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-remove</v-icon> Hvordan slette personopplysningene?<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-edit</v-icon> Hvordan endre/korrigere personopplysninger?<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-alert</v-icon> Slik blir du varslet dersom vi endrer personopplysningene<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              <v-banner
              single-line> 
              <v-icon color="blue">mdi-account-tie</v-icon> Slik kommer du i kontakt med behandlingsansvarlig<v-spacer></v-spacer>
              </v-banner>
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
        </v-expansion-panels>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
