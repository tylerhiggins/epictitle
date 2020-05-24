<template>
    <div class="construction">
        <b-container>
            <b-row>
                <b-col>
        <b-img id="logo" :src="require('@/assets/main_logo.png')" fluid/>
        <h1>An Epic Fursuit Making Website is Coming Soon...</h1>
                    <a href="https://www.facebook.com/EpicTitleCreations/">
                        <font-awesome-icon :icon="['fab','facebook-square']" size="3x"/>
                    </a>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
    export default {
        name: "construction"
    }
</script>

<style scoped>
    .construction {
        text-align: center;
    }
    #logo {
        max-width: 75%;
    }
</style>
