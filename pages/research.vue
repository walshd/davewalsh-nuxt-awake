<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="Dave's Research"
      subtitle=""
      image="/uploads/davewalsh-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3>Digital Cultural Heritage</h3>
          <p>My research is in the field of .....
          </p>

      </template>


    </main-section>
  </div>
</template>
<script>
import QuoteCard from '~/components/cards/QuoteCard'
export default {
  head() {
    return {
      title: `Research | ${this.$siteConfig.siteName}`
    }
  },
  components: { QuoteCard }
}
</script>
