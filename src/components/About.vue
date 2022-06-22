<template>
      <section id="about" class="relative py-40 bg-black text-white">
        <div class="container mx-auto px-4">
          <div class="items-center flex flex-wrap">
            <div
              class="w-full md:w-4/12 ml-auto mr-auto px-4"
              data-aos="fade-right"
            >
              <img
                alt="..."
                class="max-w-full rounded-lg shadow-lg"
                src="https://images.unsplash.com/photo-1601042879364-f3947d3f9c16?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8bmVvbiUyMGNpdHl8ZW58MHx8MHx8&w=1000&q=80"
              />
            </div>
            <div
              class="w-full md:w-5/12 ml-auto mr-auto px-4"
              data-aos="fade-left"
            >
              <div class="md:pr-12">
                <small class="text-orange-500">{{roottitle}}</small>
                <h3 class="text-4xl uppercase font-bold">{{title}}</h3>
                <p class="mt-4 text-lg leading-relaxed">
                  {{description}}
                </p>
                <ul class="list-none mt-6">
                  <li class="py-2">
                    <div class="flex items-center">
                      <div>
                        <span
                          class="font-semibold inline-block py-3 mr-3 text-orange-500"
                          ><i class="fas fa-dumbbell fa-2x"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-xl">
                          {{subject}}
                        </h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                      <div>
                        <span
                          class="font-semibold inline-block py-3 mr-3 text-orange-500"
                          ><i class="fas fa-hard-hat fa-2x"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-xl">
                         {{title1}}
                        </h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                      <div>
                        <span
                          class="font-semibold inline-block py-3 mr-3 text-orange-500"
                          ><i class="fas fa-users fa-2x"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-xl">{{title2}}</h4>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    
                    <div class="flex items-center">
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-alert-octagon"><polygon points="7.86 2 16.14 2 22 7.86 22 16.14 16.14 22 7.86 22 2 16.14 2 7.86 7.86 2"></polygon><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                      <div>
                        <span
                          class="font-semibold inline-block py-3 mr-3 text-orange-500"
                          ><i class="fas fa-users fa-2x"></i
                        ></span>
                      </div>
                      <div>
                        <h4 class="text-xl">{{title3}}</h4>
                      </div>
                    </div>
                  </li>
                </ul>
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
       logo: 'NeonCity',
       logoQR: 'QR', 
       roottitle:"QR Laboratuvarı",
       title:"Laboratuvar Blokları",
       description:"Laboratuvar içerisinde birçok başlık altında toplanan QR kodlarının NeonCity'a gönderilmesi ve okunmasını sağlayan bir uygulamadır. Laboratuvarın asıl kuruluş amacı çalışkan robotlarımızın yeni QR kodlarının API aracılığıyla oluşturulması ve sizin gibi QR savaşçılarına didik didik ayrıştırıp göstermesi üzerine kurulmuş bir uygulamadır.",
       subject:"QR Başllıkları",
       title1:"Marvel",
       title2:"League of Legends",
       title3:"Pexels"
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