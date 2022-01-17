<template>
  <div>
    <!-- Header -->
    <Header />
    <!-- End Header -->

    <!-- Main -->
    <Main />
    <!-- End Main -->

    <!-- Footer -->
    <Footer />
    <!-- End Footer -->

  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import 'bootstrap/dist/css/bootstrap.css';

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer
  },
};
</script>

<style lang="scss">
@import './style/generals.scss';
@import './style/variables.scss';

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>
