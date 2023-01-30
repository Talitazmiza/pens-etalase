<template>
    <!-- Write HTML here -->
    <div class="grid grid-cols-6 background">
        <div class="col-start-2 col-span-4">
            <div class="card">
                <div class="card-body shadow-2xl rounded-box bg-lime-200">
                    <div class="pt-6">
                        <SearchBar />
                    </div>
                    <div class="hero min-h-screen">
                        <div class="hero-content flex-col lg:flex-row-reverse">
                            <img src="https://cdn.dribbble.com/users/2577653/screenshots/14361312/media/75f287eba0e35d579cec99d119d8b88d.png?compress=1&resize=1200x900&vertical=top" class="max-w-sm rounded-lg shadow-2xl skew-y-12" /> 
                            <div class="text-black">
                                <h1 class="text-5xl font-bold">Live Project!</h1>
                                <p class="py-6">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-start-1 col-end-7 text-black bg-red-300">
                        <div class="grid grid-cols-3 gap-4 shadow-2xl">
                            <Card />
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

// JavaScript logic goes here
import Navbar from './../components/Navbar.vue';
import SearchBar from '../components/SearchBar.vue';
import Card from '../components/Card.vue';

</script>

<style>
/* CSS style component  */
</style>