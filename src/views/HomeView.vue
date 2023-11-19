<script setup>
import heading from '../components/Heading.vue'
import footercustom from '../components/Footer.vue'
import threads from '../components/ThreadPosts.vue'
</script>

<template>
  <div class="content">
    <heading/>
    <threads/>
    <footercustom id="footer"/>
  </div>
</template>

<style lang="scss" scoped>
.content {
  display: flex;
  flex-direction: column;
  flex: 1;
  height: 100vh;
}

</style>