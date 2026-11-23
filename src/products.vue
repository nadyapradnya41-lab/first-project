<script setup>
import { ref, reactive, computed, watch } from 'vue';


//const data = {link: "www.facebook.com", name:"facebook", imgUrl:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTtpGxEtRhb3A67PkBh119TTGh8oFpthFrmW_JbytfMs2pXqKYj33vBuNpyioPE_3DTK0XqvfKbpXxYYcBu3CVrf4alpt7acmkmE6WM6g&s=10", altText:"Lee Jeno", value:"ganteng"}

let idol = [
{nama: "Jeno", age: 26, gender: "male", Group:"Nct Dream"},
{nama: "Jungkook", age: 29, gender: "male", Group:"BTS"},
{nama: "Taehyung", age: 30, gender: "male", Group:"BTS"},
]
</script>



<template>
  <div v-for="(item, index) in idol" :key="index">
    <h2>{{ item.nama }}</h2>
    <p>age :{{ item.age }}</p>
    <p>gender :{{ item.gender }}</p>
    <p>Group : {{ item.Group }}</p>
  </div>
  <!-- <a :href="data.link">{{ data.name }}</a>
  <img :src=" data.imgUrl " :alt="data.altText">
  <input type="text" :value="data.value"> -->

  
</template>

  



<style scoped>
</style>