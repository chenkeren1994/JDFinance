<template>
    <section :class="$style.content">
        <img :src="item.src" alt="">
    </section>
</template>

<script>
    export default {
        data() {
            return {
                item:{
                        href: "home",
                        src: "//img12.360buyimg.com/jrpmobile/jfs/t16798/322/621991060/49914/ec0d539b/5a991ebcN932c6731.jpg?width=750&height=320"
                    }

            }
        }
    }
</script>

<style lang="scss" module>
        .content{
            margin-top: 120px;
            img{
                width: 100%;
                height: 273px;
            }
        }
</style>