<template>
  <div class="wrapper">
    <Header />

    <Main />

    <Footer />
  </div>
</template>

<script>
import { onMounted } from 'vue';
import Header from './components/header.vue';
import Main from './components/main.vue';
import Footer from './components/footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  },
  setup() {
    onMounted(() => {
      document.title = 'Sunnyside Agency | Valdi';
    });
  },
};
</script>

<style lang="scss">

#app {
  font-family: 'Barlow', sans-serif;
  // font-family: 'Fraunces', serif;
}

</style>
