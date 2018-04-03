<template>
    <div>
        <Heador/>
        <ITitle/>
        <Welfare/>
        <Active/>
        <Service/>
        <Footor/>
        <Navbar/>
    </div>
</template>

<script>
    import Heador from '../public/header.vue';
    import Footor from '../public/footer.vue';
    import Navbar from '../public/navbar.vue';
    import ITitle from './image-title.vue';
    import Welfare from './welfare.vue';
    import Active from './active.vue';
    import Service from './service.vue';
    export default {
        components: {
            Heador,
            ITitle,
            Footor,
            Navbar,
            Welfare,
            Service,
            Active
        }
    }
</script>
