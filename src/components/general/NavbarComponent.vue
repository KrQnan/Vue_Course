<template>
    <div>
        <ul class="flex flex-row justify-around">
            <li>
                <RouterLink to="/">
                    Home
                </RouterLink>
            </li>
            <li>
                <RouterLink to="/shop">
                    Shop
                </RouterLink>
            </li>
            <li>
                <RouterLink to="/pokemons">
                    Pokemons
                </RouterLink>
            </li>
        </ul>
    </div>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router';


</script>

<style scoped lang="scss">
li {
    a {
        width: 100%;
        padding: 1rem;
    }
}
</style>