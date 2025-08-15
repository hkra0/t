<script setup>
useHead({
  title: '(๑• . •๑)',
  meta: [
    { name: 'description', content: 'Private URL shortening service using Sink' },
    { name: 'viewport', content: 'width=device-width, initial-scale=1.0' },
  ],
})
</script>

<template>
  <main class="flex flex-col justify-center">
    <div class="text-center">
      <h1>tiny link service</h1>
      <div class="tinyko">
        (๑• . •๑)
      </div>
      <p>
        Private URL shortening infrastructure, using <a
          href="https://sink.cool" target="_blank" class="text-blue-500 hover:underline"
        >Sink</a>.
      </p>
    </div>
  </main>
</template>

<style scoped>
.tinyko {
  font-size: 2.5rem;
  margin: 1rem 0;
  filter: brightness(1.1);
}

h1 {
  font-size: clamp(2rem, 5vw, 3rem);
  font-weight: bolder;
  margin-bottom: 1rem;
  color: #e84393;
}

p {
  font-size: clamp(1rem, 2.5vw, 1.25rem);
  margin-bottom: 2rem;
  color: #636e72;
}
</style>
