<template>

    <div class="w-1/3 bg-slate-500 mt-8 p-4 bg-opacity-5 backdrop:backdrop-blur-2xl">
            <h1 class="text-white mb-8">Login</h1>
            <div class="flex flex-col h-full">
                <input type="text" placeholder="E-mail" id="email" class="h-12 bg-slate-500 bg-opacity-0 border-b border-white">
                <input type="text" placeholder="Password" id="password" class="h-12 bg-slate-500 bg-opacity-0 border-b border-white">
                        <hr class="border-t border-white mt-8">

                <div class="w-full flex justify-end mt-4">
                    <button class="bg-slate-600 p-2 rounded text-sm">LOGIN</button>
                </div>
            </div>
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
