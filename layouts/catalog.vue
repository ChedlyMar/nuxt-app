<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Catalog</NuxtLink>
      </nav>
    </header>
    <div>
      <slot />
    </div>
    <footer>
      <nav>
        <ul>
          <li><NuxtLink to="/home">Home</NuxtLink></li>
          <li><NuxtLink to="/catalog">Catalog</NuxtLink></li>
          <li><NuxtLink to="/contact">Contact</NuxtLink></li>
        </ul>
      </nav>
    </footer>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>