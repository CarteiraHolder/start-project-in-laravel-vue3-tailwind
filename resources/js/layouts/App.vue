<template>
    <div>
        <h1 class="text-center">Hello App!</h1>
        <p class="text-center">
            <router-link to="/" class="mx-1">Go to Home</router-link>
            <router-link to="/about" class="mx-1">Go to About</router-link>
        </p>

        <div class="text-center">
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>