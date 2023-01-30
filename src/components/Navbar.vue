<template>
    <!-- Write HTML here -->
    <div class="navbar bg-white">
        <div class="flex-1">
            <a href="https://www.pens.ac.id/" target="_blank">
                <img class="object-cover" src="logonavbar.svg" alt="Pens Logo">
                <!-- <h1>StoreFront</h1> -->
            </a>
        </div>
        <div class="flex-none gap-2">
            <button class="btn btn-ghost">Login</button>
            <div class="dropdown dropdown-end">
                <label tabindex="0" class="btn btn-ghost btn-circle avatar">
                    <div class="w-10 rounded-full">
                        <img src="https://cdn-icons-png.flaticon.com/512/1077/1077114.png" alt=""/>
                    </div>
                </label>
                <ul tabindex="0" class="mt-3 p-2 shadow menu menu-compact dropdown-content bg-white rounded-box w-52">
                    <li><a>Dashboard</a></li>
                    <li><a>Logout</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
// JavaScript logic goes here
import { UserCircleIcon } from '@heroicons/vue/24/solid'

export default {
    components: { UserCircleIcon }
}
</script>

<style>
/* CSS style component  */
</style>