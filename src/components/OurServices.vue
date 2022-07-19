<template>
   <section id="our-services" class="row mb-0">
      <div class="ms_container">
        <div class="main_title">
           <h3>See our Top Notch Services</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-4">

                <div class="col" v-for="cardItem, index in cardItems" :key="index">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i :class="`${cardItem.icon}`"></i></div>
                     <h4>{{cardItem.title}}</h4>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                     <a href="#">Read More ></a>
                  </div>
               </div>

          </div>
        </div>  
     </div>
   </section>
</template>

<script>

export default {
      name: 'OurServices',
      data(){
         return{

            cardItems: [
               {
                  icon: 'fa-brands fa-google',
                  title: 'Google SEO',
                  content: 'exercitationem obcaecati officia quos officiis sequetur aria vel excepturi, facilis nihil numquam et!',
                  callToAction: 'Read More >'
               },
               {
                  icon: 'fa-solid fa-building',
                  title: 'Brand Strategy',
                  content: 'Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!',
                  callToAction: 'Read More >'
               },
               {
                  icon: 'fa-solid fa-building',
                  title: 'Local SEO',
                  content: 'officia quos officiis vel Nesciunt magnam exercitationem obcaecati excepturi, facilis nihil numquam et!',
                  callToAction: 'Read More >'
               },
                   {
                  icon: 'fa-solid fa-chart-column',
                  title: 'Get Results',
                  content: 'officia quos officiis vel Nesciunt magnam exercitationem obcaecati excepturi, facilis nihil numquam et!',
                  callToAction: 'Read More >'
               },
            ],
        };
    }
 }

</script>

<style lang="scss" scoped>
 @import '../assets/scss/vars.scss';

#our-services{
      background-image: url(../assets/img/pattern_background.png);
      background-color: $bg-secondary-color;
      background-size: cover;
      background-repeat: no-repeat;
      background-position-x: 50%;
      background-position-y: 50%;
      min-width: 800px;
      color: $text-second;

               .ms_container{
               padding-bottom: 150px;
               
                     .main_title{
                        margin-bottom: 80px;
                           
                           p{
                              color: $text-second;
                           }
                     }

                     .ms_card{
                        background-color: $card-color;

                              .symbol{
                                 padding-top: 2rem;
                              }

                              h4{
                                 margin-top: 1.5rem;
                                 margin-bottom: 1rem;
                              }

                              p{
                                 margin-bottom: 1rem;
                              }

                              a{
                              padding-bottom: 2rem;
                              color: $text-special
                              }
                        }
               }
   }
</style>