<template>
  <v-card flat>
    <v-toolbar
      color="primary"
      dark
      extended
      flat
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </v-toolbar>

    <v-card
      class="mx-auto"
      max-width="700"
      style="margin-top: -64px;"
    >
      <v-toolbar flat>
        <v-toolbar-title class="grey--text">Title</v-toolbar-title>

        <div class="flex-grow-1"></div>

        <v-btn icon>
          <v-icon>search</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon>apps</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon>more_vert</v-icon>
        </v-btn>
      </v-toolbar>

      <v-divider></v-divider>

      <v-card-text style="height: 200px;"></v-card-text>
    </v-card>
  </v-card>
</template>
