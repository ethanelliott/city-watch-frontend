<template>
    <div v-if="cityData">
        {{ cityData.population }}
    </div>
</template>

<script>

import {mapGetters} from "vuex";

export default {
    name: "CityHome",
    data: () => ({}),
    computed: mapGetters({
        cityData: "city/cityData"
    }),
    mounted() {
    }
}
</script>
