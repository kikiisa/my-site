<template>
  <div class="breadcrumbs text-sm mt-1 mb-3">
    <ul>
      <li>
        <router-link to="/">
          <i class="bi bi-house-fill"></i>
          <span class="ms-1">Home</span>
        </router-link>
      </li>
      <li>
        <a>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            class="h-4 w-4 stroke-current"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
            ></path>
          </svg>
          
        </a>
      </li>
      <li>
        <span class="inline-flex items-center gap-2">
            <i class="bi bi-file-earmark-post"></i>
          Detail Post
        </span>
      </li>
    </ul>
  </div>
</template>
