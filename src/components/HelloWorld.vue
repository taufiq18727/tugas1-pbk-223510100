<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      <a href="" target="" rel="noopener"><img src="c:\Users\clean.user\Pictures\gmail.png" alt="gmail"  width="15" height="15">Contact: <br> +6285263855186</a><br>
      <a href="https://api.whatsapp.com/send/?phone=%2B6285263855186&text&type=phone_number&app_absent=0" target="_blank" rel="noopener"><img src="c:\Users\clean.user\Pictures\wa.png" alt="+62 852 6385 5186" width="18" height="18">085263855186</a> <br>
      <a href="https://www.instagram.com/taufiq.297?igsh=NDF5cXltbzc2ZHVz" target="_blank" rel="noopener"><img src="c:\Users\clean.user\Pictures\ig.jpeg" alt="Instagram"  width="15" height="15">taufiq.297</a><br>
      <a href="https://mail.google.com/mail/u/0/#inbox" target="_blank" rel="noopener"><img src="c:\Users\clean.user\Pictures\gmail.png" alt="gmail"  width="15" height="15">qurrahman224@gmail.com</a><br>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
