<script setup >
import LandingPage from "@/components/LandingPage.vue";
import DiscoverPage from "@/components/DiscoverPage.vue";

</script>

<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="../assets/logo 1.png" alt="logo1" class="logo" />
      </a>
      <div>
        <ul class="navbar-nav ms-auto">
          <li>
            <a class="a" href="#">SCHEDULE</a>
          </li>
          <li>
            <a class="a" href="#">GUIDLINES</a>
          </li>
          <li>
            <a class="a" href="#">ANIMALS</a>
          </li>
          <li>
            <a class="a" href="#">PLANTS</a>
          </li>
          <li>
            <a class="a" href="#">ABOUT US</a>
          </li>
          <li>
            <button class="btn">
              <img src="../assets/ticket-star.png" alt="" class="b" />Get Tickets
            </button>
          </li>
        </ul>
      </div>
    </div>
  </nav>
 
<landing-page />
<discover-page />

</template>
