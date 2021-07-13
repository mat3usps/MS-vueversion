<template>
    <v-app>
        <v-app-bar app color="deep-purple darken-4" dark> </v-app-bar>

        <v-main>
            <router-view />
        </v-main>
    </v-app>
</template>

<script>
export default {
    name: "App",

    data: () => ({
        //
    }),
};
</script>
