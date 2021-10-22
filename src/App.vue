<template>
  <main>
    <Navbar />
    <Header class="px-6 sm:px-12 md:px-28 py-6 sm:py-12 md:py-10" />
    <content>
      <Features class="mx-6 sm:mx-12 md:mx-28 my-6 sm:my-12 md:my-3"/>
      <section class="bg-blue-50 py-10">
        <Howitworks class="mx-6 sm:mx-12 md:mx-28 my-6 sm:my-12 md:my-3"/>
      </section>
      <Pricing class="mx-6 sm:mx-12 md:mx-28 my-6 sm:my-12 md:my-3"/>
      <section class="bg-blue-50 mt-28 overflow-hidden">
      <Why class="mx-6 sm:mx-12 md:mx-28 my-6 sm:my-12 md:my-20"/>
      </section>
      <Testimonials/>
      <section class="py-24 bg-blue-50 overflow-hidden">
      <Support class="mx-6 sm:mx-12 md:mx-28 my-6 sm:my-12 md:my-3"/>
      </section>
      <Footer/>
    </content>
  </main>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import Features from './components/Features.vue'
import Howitworks from './components/Howitworks.vue'
import Why from './components/Why.vue'
import Testimonials from './components/Testimonials.vue'
import Support from './components/Support.vue'
import Footer from './components/Footer.vue'
import Pricing from './components/Pricing.vue'
export default {
  components: {
    Navbar,
    Header,
    Features,
    Howitworks,
    Why,
    Testimonials,
    Support,
    Footer,
    Pricing,
  },
}
</script>

<style></style>
