<template>
  <section class="relative">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="pt-32 pb-12 md:pt-40 md:pb-20">
        <div class="text-center pb-12 md:pb-16">
          <div class="max-w-3xl mx-auto">
            <Accordion />
            <!-- <p class="text-xl text-gray-600 mb-8" data-aos="zoom-y-out" data-aos-delay="150">
              Our landing page template works on all devices, so you only have to set it up once,
              and get beautiful results forever.
            </p> -->
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Accordion from '../components/Accordion.vue'
export default {
  components: {
    Accordion
  }
}
</script>
