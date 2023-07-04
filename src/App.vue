<script setup>
</script>

<template>
  <section class="fullscreen d-flex align-items-center justify-content-center">
    <div
      class="box-content d-flex align-items-center justify-content-center border rounded-3 w-100 h-100 bg-light shadow-lg text-dark row p-5 mx-3 position-relative">
      <p class="h6 text-end position-absolute top-0 end-0 p-5">
        <RouterLink to="/">Home</RouterLink> / 
        <RouterLink to="/about">About</RouterLink>
      </p>
      <div>
        <img src="https://i.pinimg.com/564x/f2/66/a8/f266a8c46ba57287480147f3652d03f1.jpg"
          class="image is-128x128 mx-auto rounded-3" alt="">
        <p class="text-center h3 my-5">VLTs</p>
        <figcaption class="blockquote-footer text-center">
          Valentine<cite title="Source Title">'s</cite>
        </figcaption>
        <RouterView/>
      </div>
      
    </div>
  </section>
</template>

<style scoped>
</style>
