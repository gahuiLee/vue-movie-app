<template>
  <footer>
    <Logo></Logo>
    <a href="" target="_black">
      (c) {{ new Date().getFullYear() }} GAHEE
    </a>
  </footer>
</template>

<script>
import Logo from './Logo.vue'
export default {
  components: {
    Logo
  }
}
</script>

<style lang="scss" scoped>
@import "../scss/main.scss";

footer {
  padding: 70px 0;
  text-align: center;
  opacity: .3;

  .logo {
    display: block;
    margin-bottom: 4px; 
    text-decoration: none;
  }
  a{
    text-decoration: none;
  }
  
}
</style>