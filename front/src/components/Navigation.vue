<template>
    <v-toolbar flat>
        <img src="/static/img/logo-40.png">
        <v-toolbar-title class="hidden-xs-only"><img src="/static/img/app-name.png"></v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn icon to="/" exact router>
            <v-icon>home</v-icon>
        </v-btn>
        <v-btn icon to="/stages" exact router>
            <v-icon>terrain</v-icon>
        </v-btn>
        <v-spacer></v-spacer>
        <User></User>
    </v-toolbar>
</template>

<script>
    import User from './User.vue'

    export default {
        components: {
            User,
        }
    }
</script>