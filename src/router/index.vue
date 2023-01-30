<template>
    
</template>

<script>
    import HomePage from '../views/HomePage.vue';
    import LoginPage from '../views/LoginPage.vue';

    const routes = {
        '/': HomePage,
        // '/login': LoginPage
    }

    export default {
        data() {
            return {
                currentPath: window.location.hash
            }
        },
        computed: {
            currentView() {
                return routes[this.currentPath.slice(1) || '/']
            }
        },
        mounted() {
            window.addEventListener('hashchange', () => {
                this.currentPath = window.location.hash
            })
        }
    }
</script>