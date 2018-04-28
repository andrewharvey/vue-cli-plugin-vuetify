<%_ if (rootOptions.router) { _%>
<template>
  <v-container fluid>
    <v-slide-y-transition mode="out-in">
      <v-layout column align-center>
        <img src="@/assets/logo.png" alt="Vuetify.js" class="mb-5">
        <HelloWorld msg="First, solve the problem. Then, write the code." />
      </v-layout>
    </v-slide-y-transition>
  </v-container>
</template>
<%_ } _%>
