<template>
  <div class="row">
    <app-quote v-for="quote in quotes">{{ quote }}</app-quote>
  </div>
</template>

<script>
import Quote from './quote'

  export default {
    props: ['quotes'],
    components: {
      appQuote: Quote
    }
  }
</script>