<template>
  <DefaultLayout title="Home">
    <h2>aaaaaaaa</h2>
    <h2>bbbbbbbb</h2>
  </DefaultLayout>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import DefaultLayout from "@/layouts/Default/DefaultLayout.vue";

export default defineComponent({
  name: "Login",
  components: {
    DefaultLayout,
  },
});
</script>
