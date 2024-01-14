<template>

    <div class="flex flex-col bg-slate-500 p-8 bg-opacity-20 backdrop:backdrop-blur-2xl">
                <h1 class="text-white">Login</h1>
            <input type="text" id="email" class="bg-opacity-0">
            <input type="text" id="password" class="bg-opacity-0">
        </div>

</template>

<script>
import RebootLogo from './RebootLogo.vue';

export default {
    name: 'LoginForm',
    components: { RebootLogo }
}
</script>

<style scoped>



</style>
