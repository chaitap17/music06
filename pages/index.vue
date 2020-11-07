<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="10">
      <div class="text-center">
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline"> Welcome to A PLAY MUSIC. </v-card-title>
        <v-card-text>
          <p>IF YOU WANT TO VIEW PROFILE CLICK CONTiUNUE</p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="success" nuxt to="/inspire">
            Continue
            <v-icon>mdi-cursor-default-click</v-icon>
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
<script>
import VuetifyLogo from '~/components/VuetifyLogo.vue'
export default {
  components: {
    VuetifyLogo,
  },
}
</script>
