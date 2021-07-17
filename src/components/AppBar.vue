<template>
    <v-app-bar app class="app-bar" style="height: ">
        <router-link to="/" style="border: 2px solid black">
            <div class="logo"><Logo fill="#c16f10" /></div>
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
.app-bar {
    background: linear-gradient(90deg, rgba(7, 0, 18, 1) 0%, rgba(134, 19, 7, 1) 70%, rgba(193, 111, 16, 1) 100%);
}
.logo {
    margin: 5px;
    height: 80px;
    width: 100px;
    display: flex;
    align-items: center;
}
</style>
