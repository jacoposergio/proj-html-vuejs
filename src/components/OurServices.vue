<template>
   <section id="our-services" class="row mb-0">
      <div class="ms_container">
        <div class="main_title">
           <h3>See our Top Notch Services</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-4">

                <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i class="fa-brands fa-google"></i></div>
                     <h4>Google SEO</h4>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                     <a href="#">Read More ></a>
                  </div>
               </div>

             <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i class="fa-solid fa-gear"></i></div>
                     <h4>Brand Strategy</h4>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                     <a href="#">Read More ></a>
                  </div>
               </div>

               <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i class="fa-solid fa-building"></i></div>
                     <h4>Local SEO</h4>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                     <a href="#">Read More ></a>
                  </div>
               </div>

                <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="symbol"><i class="fa-solid fa-chart-column"></i></div>
                     <h4>Seo Analysis</h4>
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

}

</script>

<style lang="scss" scoped>

#our-services{
      background-image: url(../assets/img/pattern_background.png);
      background-color: blue;
      background-size: cover;
      background-repeat: no-repeat;
      background-position-x: 50%;
      background-position-y: 50%;
      min-width: 800px;
      color: white;
}

.ms_container{
  padding-bottom: 150px;
  
  .main_title{
   margin-bottom: 80px;
  }

.ms_card{
    background-color: grey;

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
        color: orange;
      }
   }
}

</style>