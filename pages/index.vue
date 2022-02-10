<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <NuxtLogo />
        <VuetifyLogo />
      </v-card>
      <v-card class="">
        <v-card-title class="headline d-flex justify-center">
          Primeiro App web dos DIAS
        </v-card-title>
        <v-card-text>
          <p>
            Bora?
          </p>
          <ul class="d-flex flex-column justify-center">
            <li>Nuxt</li>
            <li>Vuetify</li>
            <li>Vue 3</li>
          </ul>
          <div class="text-xs-right d-flex flex-column mt-5">
            <em><small>&mdash; Rafael Dias</small></em>
            <em><small>&mdash; Matheus Dias</small></em>
          </div>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
