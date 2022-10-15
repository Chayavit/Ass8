<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/Overwatch.png" alt="">
            </div>
            <div class="content">
                <h3>OVERWATCH 2</h3>
                <span>A FUTURE WORTH FIGHTING FOR</span>
                <p>CTEAM-BASED ACTION • FREE TO PLAY</p>
                <router-link to="/about" class="btn"> Play Now <i class="fas fa-user"></i> </router-link>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar } ,
    data() {
        return {
            name: 'Chayavit Wongharimart'
        
        }
    }
}
</script>

<style>
</style>