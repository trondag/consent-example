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
              Personopplysninger vi samler inn
            </v-expansion-panel-header>
            <v-expansion-panel-content>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque eu diam sed ipsum ornare ornare. Pellentesque eu orci a urna vulputate dictum a quis ligula. Donec pretium lacinia posuere. Suspendisse non diam elit. Nulla sagittis ligula quis neque facilisis, ut maximus nunc ullamcorper. Nam pharetra ipsum in magna luctus, quis elementum ligula semper. Quisque imperdiet vehicula mauris a dictum. Proin maximus accumsan neque condimentum consequat. Aliquam euismod mi laoreet sem faucibus dictum.
            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Hvordan vi bruker personopplysningene
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Hvordan vi deler dine personopplysninger med andre parter
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Hvilke parter deler hvilke personopplysninger med oss?
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
        </v-expansion-panels>
          <h3 class="mb-2 mt-2">Dine rettigheter</h3>
        <v-expansion-panels>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Hvordan eksportere personopplysninger?
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Hvordan slette personopplysningene?
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Hvordan endre/korrigere personopplysninger?
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Slik blir du varslet dersom vi endrer personopplysningene
            </v-expansion-panel-header>
            <v-expansion-panel-content>

            </v-expansion-panel-content>
          </v-expansion-panel>
          <v-expansion-panel>
            <v-expansion-panel-header>
              Slik kommer du i kontakt med behandlingsansvarlig
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
