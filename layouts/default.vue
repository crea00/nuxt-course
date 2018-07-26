<template>
  <div>
    <Header />
    <nuxt/>
  </div>
</template>

<script>
// @ : Behind the scenes by webpack which builds the project so this will be replaced with a root folder
import Header from "@/components/Header";

export default {
  components: {
    Header
  }
};
</script>

<style>
</style>
