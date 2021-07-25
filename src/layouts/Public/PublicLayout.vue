<template>
<h1>{{ msg }}</h1>
<slot></slot>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "PublicLayout",
  props: {
    msg: String,
  },
});
</script>
