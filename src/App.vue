<template>
  <div class="container">
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import PageBody from './components/PageBody.vue';
import PageFooter from './components/PageFooter.vue';

export default {
  components: {
    PageHeader,
    PageBody,
    PageFooter,
  },
};
</script>

<style>
  * {
    font-family: 'Montserrat', sans-serif;
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
  }
  body {
    display: flex;
    justify-content: center;
    background: lightgray;
  }
  .container {
    width: 1440px;
  }
  .w400 {
    font-weight: 400;
  }
  .w600 {
      font-weight: 600;
    }
  .w700 {
      font-weight: 700;
    }
</style>
