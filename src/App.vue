<script setup>
// works fine
import MyComponent2 from '@my-package';
</script>

<script setup lang="ts">
// doesn't work
import MyComponent1 from '@my-package';
</script>

<template>
  <div></div>
</template>

