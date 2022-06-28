<template>
  <header>
    <h2>{{ title }}</h2>
    <ButtonComponent text="Add Task" color="green"/>
  </header>
</template>

<script>
import ButtonComponent from './Button.vue'

export default {
  name: "HeaderComponent",
  props: {
    title: String,
  },
  components: {
    ButtonComponent,
  },
};
</script>

<style scoped>
header {
  display-flex: space-between;
  align-items: center;
  margin-botton: 20px;
}
</style>
