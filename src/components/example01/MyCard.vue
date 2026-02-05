<template>
  <VApp>
    <!-- <VTextField v-model="msg"></VTextField> -->
    <!-- <VCard>{{ msg }}</VCard> -->
    <v-container>
      <VCard>
        <VRow class="ma-0 pa-0">
          <VCol cols="6" class="bg-blue">
            <VImg
              src="https://cdn.vuetifyjs.com/docs/images/brand-kit/v-logo-circle.svg"
              :width="300"
              cover
              class="mx-auto"
            >
            </VImg>
            <h1 class="text-center">Vuetify Company</h1>
          </VCol>
          <VCol cols="6" class="d-flex flex-column justify-center align-center">
            <div>
              <div>
                <h2>John Leider</h2>
                <p>CEO, Vuetify Company</p>
              </div>
              <div class="d-flex pt-4">
                <v-icon class="mr-2">mdi-phone</v-icon>
                <p>0123 456 789</p>
              </div>
              <div class="d-flex pt-4">
                <v-icon>mdi-map-marker</v-icon>
                <p class="ml-2">Vuetify Land</p>
              </div>
              <div class="d-flex pt-4">
                <v-icon>mdi-email</v-icon>
                <p class="ml-2">john@vuetify.com</p>
              </div>
            </div>
          </VCol>
        </VRow>
      </VCard>
    </v-container>
  </VApp>
</template>
<script setup>
const msg = ref("Hello Vuetify");
</script>
