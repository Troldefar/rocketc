<template>
  <main class="main__container">
    <div class="inner__nav">
      Inner
    </div>
    <router-view class="inner__content" />
  </main>
</template>

<script>
export default {
  name: 'Main',
  setup() {
    
  },
}
</script>