<template>
  <div class="about">
    <h1>This is an about page</h1>
    <HelloWorld msg="lolbutts"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "about",
  components: {
    HelloWorld
  }
};
</script>