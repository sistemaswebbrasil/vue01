<template>
  <div>
    <h1>{{ msg }}</h1>

<div class = "p-1 my-container active-cont">
  Conteúdo Principal Aqui
  ...
  Substitua o ícone de alternância do menu de acordo com suas necessidades
  <a class="btn border-0" id="menu-btn">
    <i class = "bx bx-menu"> </i>
  </a>
</div>

  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  props: {
    msg: String,
  },
});
</script>
