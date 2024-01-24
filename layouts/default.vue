<template>
  <div>
    <header class="shadow-sm">
      <nav class="container mx-auto p-8 flex justify-between bg-white">
        <NuxtLink to="/" class="text-3xl font-bold">PA</NuxtLink>
        <ul class="flex gap-4 font-bold">
          <li><NuxtLink to="/">About</NuxtLink></li>
          <li><NuxtLink to="/works">Works</NuxtLink></li>
        </ul>
      </nav>
    </header>
  </div>

  <div class="container mx-auto h-screen p-12">
    <slot />
  </div>

  <footer class="container mx-auto p-12 flex justify-between rounded">
    <div>
      <h4>Hire me</h4>
      <p>info@pooyaali.com</p>
    </div>
    <div>
      <h4>Follow me</h4>
      <ul class="flex gap-4">
        <li><NuxtLink to="/">Linkedin</NuxtLink></li>
        <li><NuxtLink to="/">Github</NuxtLink></li>
      </ul>
    </div>

    <div>
      <NuxtLink to="/" class="text-4xl font-bold">PA</NuxtLink>
    </div>
  </footer>
</template>

<style scoped>
.router-link-exact-active {
  color: #e43359;
}
</style>
