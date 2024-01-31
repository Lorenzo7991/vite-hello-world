
<script>
import AppTitle from './AppTitle.vue';
export default {
    name: 'AppHero',
    components: {
        AppTitle,
    },
};
</script>

<template>
    <div id="jumbotron">
        <AppTitle />
    </div>
</template>

<style>
#jumbotron {
    height: 500px;
    padding-top: 210px;
    background-image: url(../../public/maxresdefault.jpg);
    background-size: cover;
    background-position: center;
    opacity: 1;
}
</style>