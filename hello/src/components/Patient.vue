<template>
  <div class="patient">Hi Patient</div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Patient extends Vue {
  @Prop() private msg!: string;
}
</script>
