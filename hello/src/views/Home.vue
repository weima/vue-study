<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Patient msg="This is my Hello"></Patient>
    <HelloWorld msg="This is my Hello"></HelloWorld>
  </div>
</template>

<script lang="ts">
  import {Component, Vue} from "vue-property-decorator"
  import Patient from "@/components/Patient.vue"
  import HelloWorld from "@/components/HelloWorld.vue"

  @Component({
    components: {
      Patient,
      HelloWorld,
    },
  })
  export default class Home extends Vue {
  }
</script>
