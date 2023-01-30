<template>
    <!-- Write HTML here -->
    <div class="navbar bg-base-100">
        <div class="flex-1">
            <a href="https://www.pens.ac.id/" target="_blank">
                <img class="object-cover h-9 w-9" src="../assets/logo.svg" alt="Pens Logo">
                <!-- <h1>StoreFront</h1> -->
            </a>
        </div>
        <div class="flex-none gap-2">
            <button class="btn btn-ghost">Login</button>
            <div class="dropdown dropdown-end">
                <label tabindex="0" class="btn btn-ghost btn-circle avatar">
                    <div class="w-10 rounded-full">
                        <img src="https://placeimg.com/80/80/people" />
                    </div>
                </label>
                <ul tabindex="0" class="mt-3 p-2 shadow menu menu-compact dropdown-content bg-base-100 rounded-box w-52">
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