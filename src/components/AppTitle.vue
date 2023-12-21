<script>
import AppHero from "./AppHero.vue"
export default {
    components: {
        AppHero
    },
    data() {
        return {
            message: "La mia prima app con Vite!"
        }
    },
}
</script>
<template lang="">
    <div>
        <h1>{{ message }}</h1>
        <AppHero />
    </div>
</template>

<style lang="">

</style>