<script setup>
  useHead({
  title: 'My App',
  meta: [
    { name: 'description', content: 'My amazing site.' },
  ],
  bodyAttrs: {
    class: 'test',
  },
})
</script>

<template>
  <div class="mx-auto w-1/2 p-4">
    <div>
      <PostItem />
    </div>
  </div>
</template>