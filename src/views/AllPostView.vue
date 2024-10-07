<script setup>
    import Card from '../components/Card.vue';
    
</script>
<template>
  <div class="home p-2">
    
    <h4 class="text-2xl mt-3 font-bold text-center"> Search Postingan Terbaru <i class="bi bi-note"></i></h4>
    <label class="input input-bordered focus:border-none border-1  mt-4 flex items-center gap-2">
      <input type="text" class="grow" placeholder="Search Post Terbaru" />
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 16 16"
        fill="currentColor"
        class="h-4 w-4 opacity-70"
      >
        <path
          fill-rule="evenodd"
          d="M9.965 11.026a5 5 0 1 1 1.06-1.06l2.755 2.754a.75.75 0 1 1-1.06 1.06l-2.755-2.754ZM10.5 7a3.5 3.5 0 1 1-7 0 3.5 3.5 0 0 1 7 0Z"
          clip-rule="evenodd"
        />
      </svg>
    </label>
    <Card class="mt-2"/>
  </div>
</template>
