<script setup>
import mainPhoto from "../assets/images/hero.svg";
import { themeColor } from "../data/items";

const heroHeading = "RabGuard";
const buttonSeeFeature = "See Features";
</script>

<template>
  <div class="untree_co-hero" id="home-section">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-12">
          <div class="dots"></div>
          <div class="row align-items-center">
            <div
              class="col-lg-7 ml-auto order-lg-2"
              data-aos="fade-right"
              data-aos-delay="400"
            >
              <img
                :src="mainPhoto"
                alt="Image"
                class="img-fluid move-right"
              />
            </div>
            <div class="col-lg-5">
              <h1 class="heading" data-aos="fade-up" data-aos-delay="0">
                {{ heroHeading }}
              </h1>
              <div class="excerpt" data-aos="fade-up" data-aos-delay="100">
                <p>
                  Our system is designed to streamline the management of animal bite patients in the Olongapo City Animal Bite Treatment Center (ABTC). This user-friendly platform simplifies patient registration, vaccination scheduling, and medical record tracking. The system ensures efficient appointment booking, reminding patients of their upcoming vaccinations to prevent missed doses.
                </p>
              </div>
              <p data-aos="fade-up" data-aos-delay="200">
                <a
                  href="#features-section"
                  class="btn btn-primary smoothscroll"
                  style="margin-right: 5px"
                  :style="[ { background: themeColor }, { borderColor: themeColor } ]"
                  >{{ buttonSeeFeature }}</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.pricing:hover {
  color: #fff !important;
}

</style>
