<template>
    <div v-for="item in items">
        <a href="#">
            <div class="card bg-blue-200 shadow-xl">
                <figure><img src="https://placeimg.com/400/225/arch" alt="Shoes" /></figure>
                <div class="card-body">
                    <h2 class="card-title">
                        {{ item.title }}
                        <div class="badge badge-secondary">NEW</div>
                    </h2>
                    <p>If a dog chews shoes whose shoes does he choose?</p>
                    <div class="card-actions justify-end">
                        <div class="badge badge-outline">Fashion</div> 
                        <div class="badge badge-outline">Products</div>
                    </div>
                </div>
            </div>
        </a>
    </div>
    
</template>

<script>
// defineProps({
    //     title: String,
    // })
    export default {
        data() {
            return {
                items: [
                { title: 'title 01' },
                { title: 'title 02' },
                { title: 'title 03' },
                { title: 'title 04' },
                { title: 'title 05' },
                { title: 'title 06' },
                { title: 'title 07' },
                { title: 'title 08' },
                { title: 'title 09' },
                { title: 'title 10' }         
                ]
            }
        }
    }
</script>

<style>

</style>