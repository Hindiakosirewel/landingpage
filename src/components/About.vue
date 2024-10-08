<script setup>
import { themeColor } from "../data/items";
import mainPhoto from "../assets/images/about.svg";

const heading = "About";
const subHeading = "About Us";
const totalMembers = "50";
const totalTeam = "20";
</script>

<template>
  <div class="untree_co-section" id="about-section">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-8" data-aos="fade-up" data-aos-delay="100">
          <img :src="mainPhoto" alt="Image" class="img-fluid" />
        </div>
        <div class="col-lg-4">
          <div class="mb-4" data-aos="fade-up" data-aos-delay="0">
            <span class="caption" :style="[{ color: themeColor }]">{{
              heading
            }}</span>
            <h2 class="heading">{{ subHeading }}</h2>
          </div>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="100">
            <p>
              We are a group of dedicated students from Gordon College, 
              working on our Capstone project aimed at addressing real-world challenges in public health. 
              Our app, the Patient Management and Vaccination Scheduling System for Animal Bite Patients, 
              is designed to assist the Olongapo City Animal Bite Treatment Center (ABTC) 
              in managing patient records and vaccination schedules more efficiently. 
            </p>
            <p>
              Our goal is to contribute to the local community by providing a digital solution that improves patient care, 
              enhances vaccine management, and ultimately helps in the prevention of rabies.
            </p>
          </div>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="200">
            <h4>Team Composition</h4> 
          <ul
            class="list-unstyled ul-check primary mb-4"
            data-aos="fade-up"
            data-aos-delay="200"
          >
            <li>Mr. Lanpher Josh Garcia</li>
            <li>Mr. Lee Silvestre</li>
            <li>Mr. Joseph David Linobo</li>
          </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
