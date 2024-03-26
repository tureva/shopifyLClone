<template>
  <section class="bg-gradient-to-b from-green-500 via-teal-500 h-screen flex flex-col justify-center items-center">
    <div class="flex items-center mt-5">
      <img src="./assets/images/sBag.png" alt="logo" class="w-10 h-10 mr-2">
      <h3 class="font-bold text-3xl italic">Shopify</h3>
    </div>
    <div class="text-elements flex flex-col items-center  p-5">
      <h1 class="mb-5 font-semibold text-4xl">Bring your ideas to life for $1/month</h1>
      <p class=" max-w-2xl mb-1 text-center">The future of business is yours to shape. Sign up for a free trial and enjoy 3 months of shopify for $1/month on select plans.</p>
      <div class=" rounded-full bg-white p-1">
        <input class="rounded-full px-5 py-2" type="email" placeholder="Enter yout email address" id="email">
        <button class="bg-black text-white px-5 py-2 rounded-full" @click="reg">Sign up</button>
      </div>
      <p class=" text-sm mt-4 text-center max-w-lg">Try shopify free for 3 days, no credit card required. By entering your email, you agree to receive marketing emails from shopify</p>
    </div>
    <div class="img-element p-20 ">
      <img src="./assets/images/greenStore.png" alt="store" class="w-32 h-32">
    </div>
  </section>
</template>

<script setup>
 
 function reg(){
  //this might stay here for a while!!
  const mail = document.getElementById('email')
  alert(`Hey there ${mail.value}! thanks for trying us. We are still in development though, stay tuned!`)
 }

</script>
