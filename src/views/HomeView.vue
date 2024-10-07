<script setup>
    import Card from '../components/Card.vue';
</script>
<template>
    <div class="home p-2">
        <div class="mt-4">
            <h1 class=" text-4xl mb-2">Hellow <strong>World 👋</strong></h1>
            <p class="lg:w-2/3 rounded-lg text-lg">Apapun Catatan Di dalam website ini murni dari pemikiran diri sendiri tanpa intervensi dari pihak manapun 🚀</p>
            <div class="group-category mt-3">
                <span class="badge badge-primary font-bold sm:p-3">Daily Post</span>
                <span class="badge badge-accent font-bold p-3 ms-2">Code</span>
                <span class="badge badge-neutral font-bold p-3 ms-2">Unek Unek</span>
                <span class="badge bg-red-600 font-bold text-white p-3 ms-2">Quotes</span>
            </div>
        </div>
        <h1 class="text-2xl font-bold mt-4 mb-4">Post Hangat Cuy</h1>
        <hr>
        <Card/>
        <button class="btn btn-accent font-bold mt-4">Lihat Semua Post <i class="bi bi-arrow-right"></i></button>
    </div>
</template>