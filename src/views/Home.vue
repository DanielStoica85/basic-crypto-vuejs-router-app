<template>
    <Hello msg="Welcome to Your Vue.js App"/>
</template>

<script>
// @ is an alias to /src
import Hello from "@/components/Hello.vue";

export default {
  name: "home",
  components: {
    Hello
  }
};
</script>
