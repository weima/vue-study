<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="This is my Hello"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Patient from "@/components/Patient.vue";

@Component({
  components: {
    Patient
  }
})
export default class Home extends Vue {}
</script>
