<script>
import TheHeader from "./components/TheHeader.vue"
import TheFooter from "./components/TheFooter.vue"
import TheMain from "./components/TheMain.vue"

export default {
  components: {
    TheHeader,
    TheFooter,
    TheMain,
  },
  data() {
    return {

    }
  }
}

</script>

<template>
  <div class="container-fluid px-0">
    <TheHeader></TheHeader>
    <TheMain></TheMain>
    <TheFooter></TheFooter>
  </div>
</template>

<style lang="scss">

</style>

