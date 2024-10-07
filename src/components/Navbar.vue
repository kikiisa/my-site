<template>
  <div class="navbar bg-slate-900 rounded-lg mt-3">
    <div class="navbar-start">
      <div class="dropdown">
        <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 text-white"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor">
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h8m-8 6h16"
            />
          </svg>
        </div>
        <ul
          tabindex="0"
          class="menu menu-sm dropdown-content bg-base-100 rounded-box z-[1] mt-3 w-52 p-2 shadow"
        >
          <li><router-link to="/" class="font-medium text-base text-dark ">Beranda</router-link></li>
          <li><router-link to="/all-post" class="font-medium text-base text-dark ">Post</router-link></li>
          <li><a class="font-medium text-base text-dark ">About</a></li>
        </ul>
      </div>
      <router-link to="/" class="btn btn-ghost text-white text-xl"><i class="bi bi-fire text-white"></i> Course Kiki</router-link>
    </div>
    <div class="navbar-end hidden lg:flex">
      <ul class="menu menu-horizontal px-1">
        <li><router-link to="/" class="font-medium text-base text-white ">Beranda</router-link></li>
        <li><router-link to="/all-post" class="font-medium text-base text-white ">Post</router-link></li>
        <li><a class="font-medium text-base text-white ">About</a></li>
      </ul>
    </div>
  </div>
</template>
