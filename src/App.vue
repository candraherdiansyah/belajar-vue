<template>
  <div>
    <navbar-component></navbar-component>
    <head-component></head-component>
    <article-component style="padding-top: 20px;"></article-component>
    <footer-component></footer-component>
  </div>
</template>

<script setup>
import 'flowbite/dist/flowbite'
import ArticleComponent from './components/ArticleComponent.vue'
import HeadComponent from './components/HeadComponent.vue'
import NavbarComponent from './components/NavbarComponent.vue';
import FooterComponent from './components/FooterComponent.vue'
</script>

<style></style>