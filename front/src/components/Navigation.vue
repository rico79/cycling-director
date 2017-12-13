<template>
    <v-toolbar flat>
        <v-btn fab color="blue-grey lighten-4">
            <img src="/static/img/logo-40.png" alt="Cycling Director">
        </v-btn>
        <v-toolbar-title class="hidden-xs-only">Cycling Director</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn icon to="/" exact router>
            <v-icon>home</v-icon>
        </v-btn>
        <v-btn icon to="/coursecreator" exact router>
            <v-icon>create</v-icon>
        </v-btn>
    </v-toolbar>
</template>-