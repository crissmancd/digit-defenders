<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <div class="headline">
      <p>Cold fingers, sweaty palms?</p>
      <p><em>Get a Grip</em></p>
    </div>

    <img src="./assets/logo.png" class="logo" alt="Digit Defenders Finger Gloves" />

    <p class="coming-soon">Coming Soon!</p>
  </div>
</template>

<style scoped>
.headline {
  text-align: left;
  margin-bottom: 4rem;
}

.headline p {
  font-size: clamp(2rem, 5vw, 4rem);
  font-weight: 700;
  text-transform: uppercase;
  line-height: 1;
  margin: 0;
}
.headline em {
  color: var(--orange);
  font-size: clamp(1em, 13vw, 2.5em);
  font-style: normal;
  letter-spacing: .1em;
}
.logo {
  max-height: 30rem;
}
.coming-soon {
  font-size: clamp(2rem, 5vw, 4rem);
  font-style: italic;
  font-weight: 700;
  margin-top: 1em;
}
</style>
