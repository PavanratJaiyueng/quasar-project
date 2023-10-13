<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
  </div>
  <InputPage/>
  <FunctionPage/>
</template>


<script>
import InputPage from './InputPage.vue';
import FunctionPage from './FunctionPage.vue'

export default {
  name: 'HtmlComponent',
  components:{
    InputPage
    ,FunctionPage
  },
  data() {
    return {
      title: 'Pavanrat jaiyueng',
    }
  },
}
</script>

<style scoped></style>