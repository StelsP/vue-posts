<template>
  <header class="container section-header offset">
    <h1 class="title">Main Page</h1>
    <nav class="nav">
      <router-link to="/posts">Posts</router-link>
      <router-link to="/about">About</router-link>
    </nav>
  </header>
</template>
<script>
export default {};
</script>
<style scoped>
.nav {
  margin-inline: auto;
  display: flex;
  gap: 3rem;
}
</style>
