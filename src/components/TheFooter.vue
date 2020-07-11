<template>
  <footer>
    <div class="container">
      <router-link class="logo-font" :to="{ name: 'home', params: {} }">
        Twitter-Post
      </router-link>
    </div>
  </footer>
</template>

<script>
export default {
  name: "RwvFooter"
};
</script>
