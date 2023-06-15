<script>
import PageHeader from './components/PageHeader.vue'
import PageFooter from './components/PageFooter.vue'

export default {
  components: {

    PageHeader,
    PageFooter

  }
}
</script>

<template>

  <PageHeader/>
  <PageFooter/>
  
</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;

</style>
