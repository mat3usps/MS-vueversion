<template>
    <v-app-bar
        app
        style="height: 70px; background: linear-gradient(90deg, rgba(7,0,18,1) 0%, rgba(134,19,7,1) 70%, rgba(193,111,16,1) 100%);"
        dark
    >
        <router-link to="/">
            <div class="logo"><Logo /></div>
        </router-link>
    </v-app-bar>
</template>

<script>
import Logo from "./Logo.vue";

export default {
    name: "AppBar",
    components: {
        Logo,
    },
};
</script>

<style scoped>
.logo {
    height: 150px;
    width: 150px;
    display: flex;
    align-items: center;
}
</style>
