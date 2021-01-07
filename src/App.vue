<template>
  <div id="app">
    <nav id="nav">
      <navigation />
      
    </nav>
    <main>
      <router-view ></router-view>
    </main>
  </div>
</template>



<script>
import Navigation from "./components/Navigation.vue";
export default {
  components: {
    Navigation,
  },
};
</script>