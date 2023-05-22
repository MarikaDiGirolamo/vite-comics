<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppBlueBand from './components/AppBlueBand.vue';
import AppFooter from './components/AppFooter.vue';

// import HelloWorld from './components/HelloWorld.vue'
export default {
  components: {
    AppHeader,
    AppMain,
    AppBlueBand,
    AppFooter
  },
  data() {
    return {

    }
  },
  methods() {

  },
  mounted() {

  }

}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppBlueBand />
  <AppFooter />
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}</style>
