<template>
    <div id="app" style="margin:auto;width:30%">
        <!--<Home msg="Hello world!" />-->
        <digital-clock :blink="true" :displaySeconds="true" />
    </div>
</template>

<script>
    //import Home from './components/Home.vue';
    import DigitalClock from "./components/Clock.vue";

    export default {
        name: 'app',
        components: {
            //Home
            DigitalClock
        }
    };
</script>

<style>
    .clock {
        color: black;
        padding: 0.3rem 0.6rem;
        font-size: 3rem;
        font-family: "Menlo", monospace;
    }
</style>

