# IndexPage.vue
<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
  </div>
<InputPage/>
<FunctionPage/>
</template>
<script>


import InputPage from 'src/pages/InputPage.vue';
import FunctionPage from 'src/pages/FunctionPage.vue';


export default {
  name: 'HtmlComponent',
  components: {
    InputPage,
    FunctionPage
  },  
  data() {
    return {
      title: 'ภัสนุพงค์ แสนศักดิ์หาญ 6504101368.',
    }
  },
  components: { FunctionPage,InputPage}

}
</script>

<style scoped></style>