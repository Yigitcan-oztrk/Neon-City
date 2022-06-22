<template>
    <section class="pb-20 relative block bg-black text-white">
        <div
          class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
          style="height: 80px; transform: translateZ(0px)"
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
        <div class="container mx-auto px-4 lg:pt-24 lg:pb-64 pb-10 pt-20">
          <div class="flex flex-wrap text-center justify-center">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold text-white uppercase">
                {{contactHeader}}
              </h2>
              <p class="text-lg leading-relaxed mt-4 mb-4">
             {{contactDesc}}
              </p>
            </div>
          </div>
        </div>
      </section>
</template>

<style>

</style>

<script>
export default {
  data() {
    return {
      logo: "NeonCity",
      logoQR: "QR",
contactHeader:"İletişim",
contactDesc:"Herhangi bir soru sormak, Laboratuvar işleyişi hakkında sorularınız için bizimle iletişime geçin."
    };
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
};

</script>