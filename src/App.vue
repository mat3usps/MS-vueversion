<template>
    <v-app>
        <AppBar />

        <v-main style="display: flex; align-items: center;">
            <router-view />
        </v-main>
    </v-app>
</template>

<script>
import AppBar from "./components/AppBar.vue";

export default {
    name: "App",
    components: {
        AppBar,
    },
    data() {},
};
</script>
