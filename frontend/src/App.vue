<template>
  <section class="flex flex-col justify-center items-center">
    <nav class="flex justify-center item-center py-5 shadow-lg w-full text-lg text-gray-900">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>

  </section>
    

  
</template>


