<template>
   <section id="our-agency" class="row mb-0">
     <div class="ms_container">
        <div class="main_title">
           <h3>Mett the new Agency SEO Template from The Avada Team</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-3">

                <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i class="fa-solid fa-road"></i></div>
                     <h4>Estabilish Goals</h4>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                  </div>
               </div>

             <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i class="fa-solid fa-video"></i></div>
                     <h4>Estabilish Goals</h4>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                  </div>
               </div>

               <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i class="fa-solid fa-droplet"></i></div>
                     <h4>Estabilish Goals</h4>
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
    
}

</script>

<style lang="scss" scoped>

#our-agency{
   background-color: red;
}
.ms_container{
  
  .main_title{
   margin-bottom: 80px;
  }

.ms_card{
   background-color: beige;

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

</style>