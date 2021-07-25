<template>
  <!-- <main> -->
<router-view />
  <!-- <div class="container-fluid overflow-hidden">
    <nav-bar />
    <div class="row vh-100 overflow-auto">
      <side-bar></side-bar>
      <router-view />

      <footer-bar></footer-bar>
    </div>
  </div> -->
  <!-- <div class="container-fluid overflow-hidden">
      <div class="row vh-100 overflow-auto">
        <side-bar></side-bar>
        <div class="col d-flex flex-column h-sm-100">
          <main class="row overflow-auto">
            <div class="col pt-4">
              <router-view />
            </div>
          </main>
          <Footer />
        </div>
      </div>
    </div> -->
  <!-- </main> -->
</template>

<script lang="ts">
import { defineComponent } from "vue";
import NavBar from "@/components/NavBar.vue";
import SideBar from "@/components/SideBar.vue";
//import Footer from "@/components/FooterBar.vue";
import FooterBar from "@/components/FooterBar.vue";

export default defineComponent({
  components: {
    // SideBar,
    // NavBar,
    // FooterBar,
  },
});
</script>

<style>
</style>
