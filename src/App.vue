<template>
  <div>
    <app-header></app-header>
    <contador></contador>
    <Contador></Contador>
    <ContadorInfo></ContadorInfo>
    <AppHeader />
  </div>
</template>

<script>
import AppHeader from "./components/shared/AppHeader.vue";
import Contador from "./components/contador/Contador.vue";
import ContadorInfo from "./components/contador/ContadorInfo.vue";

export default {
  components: {
    Contador,
    AppHeader,
    ContadorInfo,
  },
};
</script>