<template>
  <div class="wrapper">
    <NavBar />
    <main class="container-fluid">
      <div class="row">
        <router-view />
      </div>
    </main>
    <Footer />
  </div>
</template>
<script>
import Footer from './components/Footer.vue'
import NavBar from './components/NavBar.vue'
export default {
  components: {
    NavBar,
    Footer
  }
}
</script>
<style src="@/assets/css/style.css"></style>
