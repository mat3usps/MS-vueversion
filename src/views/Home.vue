<template>
    <div>
        <label for="logo" style="display: flex; align-items: center; justify-content: center">
            <img id="logo" src="../assets/images/star.gif" alt="Logo" />
            <Logo fill="#000000" style="z-index: 10; width: 500px; position: absolute" />
        </label>
        <button>Galeria</button>
    </div>
</template>

<script>
import Logo from "../components/Logo.vue";
export default {
    components: { Logo },
    name: "Home",
};
</script>

<style scoped>
#logo {
    width: 250px;
    border-radius: 50%;
    margin: 15px;
    z-index: 1;
}
</style>
