<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header class="pt-3 pb-3 bg-red-500 flex justify-between">
    <div>
      <p>Logo</p>
    </div>
    <div>
      <nav>
        <ul class="flex">
          <li><a target="_blank" href="https://www.iim.fr/">IIM</a></li>
          <li><a href="https://www.iim.fr/">IIM</a></li>
          <li><a href="https://www.iim.fr/">IIM</a></li>
        </ul>
      </nav>
    </div>
    
  </header>

  <main>
    
    <!-- <TheWelcome /> -->
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
