<template>
    <div>
        <Heador/>
        <Slider/>
        <Ada/>
        <Money/>
        <Adb/>
        <Finance/>
        <Footor cname="mfooter"/>
        <Navbar/>
    </div>
</template>

<script>
    import Heador from '../public/header.vue';
    import Footor from '../public/footer.vue';
    import Navbar from '../public/navbar.vue';
    import Slider from './mslider.vue';
    import Ada from './ada.vue';
    import Money from './money.vue';
    import Adb from './adb.vue';
    import Finance from './finance.vue';

    export default {
        components: {
            Heador,
            Slider,
            Footor,
            Navbar,
            Ada,
            Money,
            Adb,
            Finance
        }
    }
</script>
<style lang="scss">
    .mfooter{
        ul{
            li:first-child{
                display: none;
            }
        }
    }
</style>
