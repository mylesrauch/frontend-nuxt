<template>
  <v-data-table :headers="headers"
  :items="logs"
  :sort-by="created"
  class="elevation-1"
  >
    <template v-slot:top>
      <v-toolbar
      
      >
        <v-toolbar-title> Logs </v-toolbar-title>
      </v-toolbar>
    </template>
  </v-data-table>
</template>