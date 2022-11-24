<script setup>
import AppNavigation from "./components/AppNavigation.vue"
import AppList from "./components/AppList.vue"
import AppFooter from "./components/AppFooter.vue"
import Button from "./components/AppHeader.vue"
</script>

<script>
export default {
  name: "App",
  components: {
    Button
  }
};
</script>

<template>    
  <AppHeader />
  <div id="App">
  <Button btnText="Eldritch Horror"/>
  </div>
  <AppNavigation />
  <AppList />
  <AppFooter />
</template>

