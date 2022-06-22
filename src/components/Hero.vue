<template>
    <div id="app"
        class="relative pt-16 pb-32 flex content-center items-center justify-center"
        style="min-height: 95vh"
      >
        <div
          class="absolute top-0 w-full h-full bg-top bg-cover"
          style="
            background-image: url('https://images.pling.com/img/00/00/62/69/92/1723696/neon-city-141.jpg');
          "
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-75 bg-black"
          ></span>
        </div>
        <div class="container relative mx-auto" data-aos="fade-in">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
              <div>
                <h1 class="text-white font-semibold text-5xl">
                  {{logo}} <span class="text-orange-500">{{logoQR}}</span>
                </h1>
                <p class="mt-4 text-lg text-gray-300">
                  {{acquaintance}}
                </p>
                <a
                  href="#"
                  class="bg-transparent hover:bg-orange-500 text-orange-500 font-semibold hover:text-white p-4 border border-orange-500 hover:border-transparent rounded inline-block mt-5 cursor-pointer"
                  >{{button}}</a
                >
              </div>
            </div>
          </div>
        </div>
        <div
          class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
          style="height: 70px; transform: translateZ(0px)"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon points="2560 0 2560 100 0 100"></polygon>
          </svg>
        </div>
      </div>

</template>

<style>

</style>

<script>
// import { createApp } from 'vue'

export default {
  data() {
    return {
       logo: 'NeonCity',
       logoQR: 'QR', 
       acquaintance: 'NeonCity QR Dünyasına hoş geldin. içeride QR Code ayrıştırıcı robotlarımız senin ve senin gibi olan QR savaşçıları için ayrıştırma işlemlerini tıkır tıkır yapıyor. Robotlarımınız neler yaptığına birlikte göz atalım mı? 🤖', 
      button: 'QR Laboratuvarı'
       }
  },
  // computed: {
  //   // readonly
  //   aDouble() {
  //     return this.a * 2
  //   },
  //   // writable
  //   aPlus: {
  //     get() {
  //       return this.a + 1
  //     },
  //     set(v) {
  //       this.a = v - 1
  //     }
  //   }
  // },
  // created() {
  //   console.log(this.aDouble) // => 2
  //   console.log(this.aPlus) // => 2

  //   this.aPlus = 3
  //   console.log(this.a) // => 2
  //   console.log(this.aDouble) // => 4
  // }
}
</script>