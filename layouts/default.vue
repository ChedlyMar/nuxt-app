<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt App</NuxtLink>
        <ul>
          <li><NuxtLink to="/home">Home</NuxtLink></li>
          <li><NuxtLink to="/catalog">Catalog</NuxtLink></li>
          <li><NuxtLink to="/contact">Contact</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <div>
      <slot />
    </div>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>