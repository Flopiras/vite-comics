<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'dc',
  components: { AppHeader, AppMain, AppFooter },
  data() {
    return {
      links: [
        {
          text: 'Characters',
          url: '#',
          current: false,
        },
        {
          text: 'Comics',
          url: '#',
          current: true,
        },
        {
          text: 'Movies',
          url: '#',
          current: false,
        },
        {
          text: 'TV',
          url: '#',
          current: false,
        },
        {
          text: 'Games',
          url: '#',
          current: false,
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false,
        },
        {
          text: 'Videos',
          url: '#',
          current: false,
        },
        {
          text: 'Fans',
          url: '#',
          current: false,
        },
        {
          text: 'News',
          url: '#',
          current: false,
        },
        {
          text: 'Shop',
          url: '#',
          current: false,
        },
      ],
    }
  }
}
</script>

<template>
  <!-- header -->
  <AppHeader />
  <!--main  -->
  <AppMain />
  <!-- footer -->
  <AppFooter />
</template>

<style>
/* reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* generics */
.container {
  max-width: 1200px;
  margin: 0 auto
}

ul {
  list-style-type: none;
}
</style>