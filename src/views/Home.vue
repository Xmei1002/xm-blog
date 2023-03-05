<template>
  <div class="home">
    <div class="banner">
      <Navigation></Navigation>
      <Meteor class="meteor"></Meteor>
    </div>
    <ul>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
      <li>1</li>
    </ul>
  </div>
</template>

<script setup>
  import Navigation from '@/components/Navigation.vue';
  import Meteor from '@/components/Meteor.vue';
  import Search from '@/components/Search.vue'
</script>

<style>
  .home,.banner{
    width: 100%;
    height: 100%;
    /* background-color: pink; */
  }
  .meteor{
    z-index: -1;
    overflow: hidden;
  }
  /* .banner::after{
    display: block;
    width: 100%;
    height: 100%;
    background-color: pink;
    content: '';
    position: absolute;
    top: 0%;
    left: 0;
    z-index: -1;
    background-image: url('@/assets/bgi1.png');
    background-size: 100%;
  } */
</style>