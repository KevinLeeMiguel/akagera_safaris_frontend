<script setup>
import WelcomeItem from './WelcomeItem.vue'
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <WelcomeItem>
    <p class="text-body text-center text-dark">
      <nav>
        <RouterLink to="/about">
          <button class="btn btn-md btn-success mb-4 mt-2 text-center">Book Now</button>
        </RouterLink>
      </nav>
      <span class="text-md-center">
        Embark on a wild adventure through the untamed wilderness of <strong>Akagera National Park</strong> with our
        Safari tours. Explore the breathtaking landscapes of this stunning park and witness its
        diverse wildlife up close, from majestic <strong>elephants</strong> to graceful <strong>giraffes</strong> and stealthy predators
        like <strong>lions</strong> and <strong>leopards</strong>. With our expert guides and top-notch accommodations, you'll have an
        unforgettable experience that will leave you with memories to last a lifetime. Book your
        Safari tour today and discover the wonders of Akagera National Park.
      </span>
    </p>
  </WelcomeItem>

</template>
