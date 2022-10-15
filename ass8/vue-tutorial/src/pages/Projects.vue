<template>
    <div>
        <Navbar />
        <section class="projects">
            <h1 class="heading"> <span>Game</span>  trailer </h1>
            <h3>Overwatch2 launches October 4!</h3>
            <p>Prepare yourselves for a  one-of-a-kind, action-packed, free-to-play experience with new maps, new modes, and new heroes. </p>
            <div class="box-container">
                <iframe width="720" height="405" src="https://youtu.be/LGgqyer-qr4"
                    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; 
            gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar }
}
</script>

<style>
</style>