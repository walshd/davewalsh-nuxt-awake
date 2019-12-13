<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="Dave's Work"
      subtitle=""
      image="/uploads/davewalsh-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3>Web work</h3>
          <p>My web work .....
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
