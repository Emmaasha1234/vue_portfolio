<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="https://media.licdn.com/dms/image/D4D03AQHVZLU5LRb95A/profile-displayphoto-shrink_400_400/0/1712836024157?e=1719446400&v=beta&t=C7mS11XUffqQDk7T3bw4iuUOU6INkGuHW8ZRl7vgZ1I" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Emmaculate Asha" />
    </div>
  </header>

  <main>
    <TheWelcome />
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
