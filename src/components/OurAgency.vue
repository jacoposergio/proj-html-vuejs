<template>
   <section id="our-agency" class="row mb-0">
     <div class="ms_container">
        <div class="main_title">
           <h3>Mett the new Agency SEO Template from The Avada Team</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-3">

                <div class="col" v-for="cardItem, index in cardItems" :key="index">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i :class="`fa-solid ${cardItem.icon}`"></i></div>
                     <h4>{{cardItem.title}}</h4>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                  </div>
               </div>

          </div>
        </div>  
        <div class="desk-image">
           <img src="../assets/img/agency-seo-desk-front-1200x570.jpg" alt="desk-image" />
        </div>       
     </div>
   </section>
</template>

<script>
export default {
    name: 'OurAgency',
    data(){
      return{

         cardItems: [
            {
              icon: 'fa-road',
              title: 'Estabilish Goals',
              content: 'exercitationem obcaecati officia quos officiis sequetur aria vel excepturi, facilis nihil numquam et!'
           },
            {
              icon: 'fa-video',
              title: 'Work with a team',
              content: 'Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!'
           },
            {
              icon: 'fa-droplet',
              title: 'Get Results',
              content: 'officia quos officiis vel Nesciunt magnam exercitationem obcaecati excepturi, facilis nihil numquam et!'
           },
         ],
      };
    }
}

</script>

<style lang="scss" scoped>
 @import '../assets/scss/vars.scss';

#our-agency{
   .ms_container{
     
     .main_title{
      margin-bottom: 80px;

      p{
         color: $subtext-color;
      }
     }
   
   .ms_card{

      background-color: $text-second;
   
         .symbol{
            padding-top: 2rem;
         }
   
         h4{
            margin-top: 1.5rem;
            margin-bottom: 1rem;
         }
   
         p{
            margin-bottom: 2rem;
         }
   
      }
   
       .desk-image{
         width: 90%;
         margin: 50px auto 0 auto;
        }
   
   }
}

</style>