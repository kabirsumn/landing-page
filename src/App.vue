<template>
  <h1 @click="getForm">welcome</h1>
  <Form v-if="showForm" />
</template>

<script>
import Form from './components/Form.vue';

export default {
  name: 'App',
  components: { Form },
  data() {
    return {
      showForm: false,
    };
  },
  methods: {
    getForm() {
      this.showForm = true;
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
