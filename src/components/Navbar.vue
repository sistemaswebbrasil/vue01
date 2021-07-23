<template>
  <nav class="py-2 bg-light border-bottom">
    <div class="container d-flex flex-wrap">
      <ul class="nav me-auto">
        <li class="nav-item">
          <a href="#" class="nav-link link-dark px-2 active" aria-current="page"
            >Home</a
          >
        </li>
        <li class="nav-item">
          <a href="#" class="nav-link link-dark px-2">Features</a>
        </li>
        <li class="nav-item">
          <a href="#" class="nav-link link-dark px-2">Pricing</a>
        </li>
        <li class="nav-item">
          <a href="#" class="nav-link link-dark px-2">FAQs</a>
        </li>
        <li class="nav-item">
          <a href="#" class="nav-link link-dark px-2">About</a>
        </li>
      </ul>
      <ul class="nav">
        <li class="nav-item">
          <a href="#" class="nav-link link-dark px-2">Login</a>
        </li>
        <li class="nav-item">
          <a href="#" class="nav-link link-dark px-2">Sign up</a>
        </li>
      </ul>
                <button class="btn float-end" data-bs-toggle="offcanvas" data-bs-target="#offcanvas" role="button">
                <i class="bi bi-arrow-right-square-fill fs-3" data-bs-toggle="offcanvas" data-bs-target="#offcanvas"></i>
            </button>      
    </div>
  </nav>
</template>


<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "NavBar",
});
</script>
