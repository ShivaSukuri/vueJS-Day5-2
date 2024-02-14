<template>
<div class="content">
<a :href="MTrailer" style="  text-decoration:none;
    color:black;">
<img :src="MSrc">
<h2>{{MName}}</h2></a>
</div>
</template>
<script setup>
defineProps(["MName","MSrc","MTrailer"])
</script>
<style>
.content {
  border: 2px solid black;
  height: 350px;
  width: 100%; 
}

.content img {
  width: 100%; 
  height: 250px;

}

.content h2 {
  margin: 0;
  padding: 8px;
  text-align: center;
}
/* a{
    text-decoration:none;
    color:black;
} */
</style>