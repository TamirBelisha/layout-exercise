<template>
  <section>
    <app-header></app-header>
    <app-hero></app-hero>
    <features-preview></features-preview>
    <stay-productive></stay-productive>
    <reviews/>
    <app-footer></app-footer>
  </section>
</template>

<script>
import appHeader from './components/app-header.vue'
import appHero from './components/app-hero.vue'
import featuresPreview from './components/features-preview.vue'
import stayProductive from './components/stay-productive.vue'
import reviews from './components/reviews.vue'
import appFooter from './components/app-footer.vue'
export default {
  name: '',
  data() {
    return {}
  },
  methods: {},
  computed: {},
  components: {
    appHeader,
    appHero,
    featuresPreview,
    stayProductive,
    reviews,
    appFooter
  },
}
</script>

<style></style>
