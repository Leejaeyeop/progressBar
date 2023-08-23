<template>
    <ProgressBar :cur-progress="50" />
</template>

<script>
import ProgressBar from "./components/ProgressBar.vue";

export default {
    name: "App",
    components: {
        ProgressBar,
    },
};
</script>

<style></style>
