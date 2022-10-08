<template>
    <div>
        <Navbar />
        <section class="home">
            <div class="image">
                <img src="images/profile.png" alt="">
            </div>
            <div class="content">
                <h3>hi, i am {{name}}</h3>
                <span>{{motto}}</span>
                <p>{{content}}</p>
                <router-link to="/about" class="btn"> about me <i class="fas fa-user"></i> </router-link>
            </div>
        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar },
    data() {
         return {
            name: 'Anusa khongkasem',
            motto: 'I belive,I can fly',
            content: 'วันไหนที่ร้องให้วันนั้นคือแมลงเข้าตา',
         } 
}
}
</script>

<style>

</style>