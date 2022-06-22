<template>
     <section class="relative block py-24 lg:pt-0 bg-black">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
            <div class="w-full lg:w-6/12 px-4">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300"
                data-aos="fade-up-right"
              >
                <div class="flex-auto p-2 lg:p-10 bg-orange-500 text-white">
                  <h4 class="text-2xl font-semibold">{{robotName}}</h4>
                  <p class="leading-relaxed mt-1 mb-4">
                  {{RobotMessage}}</p>
                  <div class="relative w-full mb-3 mt-8">
                    <label
                      class="block uppercase text-xs font-bold mb-2"
                      for="Tam Adınız"
                      >{{contactName}}</label
                    ><input
                      type="text"
                      class="px-3 py-3 bg-gray-500 placeholder-gray-400  rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                      placeholder="Full Name"
                      style="transition: all 0.15s ease 0s"
                    />
                  </div>
                  <div class="relative w-full mb-3">
                    <label
                      class="block uppercase text-xs font-bold mb-2"
                      for="email"
                      >{{contactEmail}}</label
                    ><input
                      type="email"
                      class="px-3 py-3 bg-gray-500 placeholder-gray-400 rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                      placeholder="Email"
                      style="transition: all 0.15s ease 0s"
                    />
                  </div>
                  <div class="relative w-full mb-3">
                    <label
                      class="block uppercase text-xs font-bold mb-2"
                      for="Mesajınız"
                      >{{contactMessage}}</label
                    ><textarea
                      rows="4"
                      cols="80"
                      class="px-3 py-3 bg-gray-500 placeholder-gray-400 rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                      placeholder="Type a message..."
                    ></textarea>
                  </div>
                  <div class="text-center mt-6">
                    <button
                      class="bg-gray-900 text-white active:bg-gray-700 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1"
                      type="button"
                      style="transition: all 0.15s ease 0s"
                    >
                      {{sendMail}}
                    </button>
                  </div>
                </div>
              </div>
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
      robotName:"İletişim Formu",
      RobotMessage:"Atmış olduğunuz mailler Robot<MA-342Z-IL> tarafınddan ayrıştırıldıktan en geç 24 saat sonra tarafınıza Mail olarak cevaplandırılacaktır ",
      contactName:"Adınız",
      contactEmail:"Email Adresiniz",
      contactMessage:"Mesajınız",
      sendMail:"Gönder"
      
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

