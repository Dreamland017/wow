<template>
    <div>
        <Navbar />
        <section class="projects">
            <h1 class="heading"> <span>my</span> projects </h1>
            <h3>{{project_name}}</h3>
            <p>{{project_detail}}</p>
            <div class="box-container">
                <iframe width="1140" height="641" src="https://www.youtube.com/embed/eYAd4uDotF0" title="Yuika - Sukidakara (Lyric Video)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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
            project_name: 'Sukidakara',
            project_detail: 'Yuika - Sukidakara (Lyric Video',
         } 
}
}
</script>

<style>

</style>