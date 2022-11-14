<script setup>
defineProps({
    nama:{
        type:String,
        default: "anton",
    },
    role:String
 });
</script>

<template>
      <div class="navbar">
        <div class="col-header">
          <img class="images-hero" src="../assets/anton.jpg" alt="anton" />
        </div>
        <div class="col-header">
          <h1>{{ nama }}</h1>
          <p>{{ role }}</p>
          <div class="btn-header">
            <button type="submit">Download CV</button>
            <button type="submit">Readme</button>
          </div>
        </div>
      </div>
</template>