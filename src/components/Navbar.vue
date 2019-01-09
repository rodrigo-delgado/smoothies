<template>
    <div class="navbar">
        <nav class="nav-extended indigo darken-2">
            <div class="nav-content">
                <router-link to="">
                    <span class="nav-title">Smothies</span>
                </router-link>
                <a href="" class="btn-floating btn-large halfway-fab green">
                    <router-link to="">
                        <i class="material-icons">add</i>
                    </router-link>
                </a>    
            </div>
        </nav>
    </div>
</template>

<script>

export default {
    name: 'Navbar',
    data() {
        
    }
}
</script>

<style scoped>
.navbar nav{
    padding: 0 20px;
}
</style>
