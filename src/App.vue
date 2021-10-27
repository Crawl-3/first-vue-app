<template>
  <Header />
  <Content />
  <Footer />
</template>

<style lang="scss">
* {
  padding: 0px;
  margin: 0px;
  text-decoration: none;
  outline: none;
  box-sizing: border-box;
  list-style: none;
  border: 0;
}

/* styling */
body {
  height: 100vh;
  background: #222;
  color: #fff;
}

button {
  cursor: pointer;
  padding: 12px 15px;
  border-radius: 3px;
  font-weight: 600;
  font-size: 1rem;
  font-family: 'Gill Sans', sans-serif;
  transition: background 150ms ease-in-out;
  &.primary {
    background: #35b87d;
    &:hover {
      background: #208d5c;
    }
  }
}

#app {
  height: 100%;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
    'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: 400;
  font-size: 1.1rem;
  letter-spacing: 0.04rem;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

<script lang="ts">
import Header from '@/components/layout/Header.vue';
import Content from '@/components/layout/Content.vue';
import Footer from '@/components/layout/Footer.vue';

export default {
  components: { Header, Content, Footer },
};
</script>
