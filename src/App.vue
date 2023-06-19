<script>
import PageHeader from './components/PageHeader.vue'
import PageMain from './components/PageMain.vue'
import PageFooter from './components/PageFooter.vue'

export default {
  components: {

    PageHeader,
    PageMain,
    PageFooter

  },
  data() {
      return {
        menu: [
          {
            text: "HOME",
            url: "#",
            current: true,

          },
          {
            text: "ABOUT",
            url: "#",
            current: false,

          },
          {
            text: "COURSES NEW",
            url: "#",
            current: false,

          },
          {
            text: "EVENTS",
            url: "#",
            current: false,

          },
          {
            text: "FACILITIES",
            url: "#",
            current: false,

          },
          {
            text: "NEWS",
            url: "#",
            current: false,

          },
          {
            text: "ADMISSION APPLY",
            url: "#",
            current: false,

          },
          
        ]
      }
    }

}

</script>

<template>

  <PageHeader :links="menu"/>
  <PageMain/>
  <PageFooter/>
  
</template>

<style lang="scss">

@use './styles/partials/variables.scss' as *;
@use './styles/general.scss' as *;

</style>
