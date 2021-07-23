<template>
  <main>
    <nav-bar></nav-bar>
                <button class="btn float-end" data-bs-toggle="offcanvas" data-bs-target="#offcanvas" role="button">
                <i class="bi bi-arrow-right-square-fill fs-3" data-bs-toggle="offcanvas" data-bs-target="#offcanvas"></i>
            </button>
    <div class="container-fluid overflow-hidden">
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
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import NavBar from "@/components/Navbar.vue";
import SideBar from "@/components/SideBar.vue";
import Footer from "@/components/Footer.vue";

export default defineComponent({
  components: {
    NavBar,
    SideBar,
    Footer,
  },
});
</script>

<style>
</style>
