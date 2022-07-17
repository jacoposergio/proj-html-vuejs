<template>
   <section id="our-news">
     <div class="ms_container">
        <div class="main_title">
           <h3>Our News</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-3">

                <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="img_container">
                         <img src="../assets/img/related-service-2-700x441.jpg" alt="">
                     </div>
                     <h4>Why you need a SEO Agency now</h4>
                     <div class="ms_subtitle">November 1st, 2017</div>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                  </div>
               </div>
            
                <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="img_container">
                         <img src="../assets/img/related-service-2-700x441.jpg" alt="">
                     </div>
                     <h4>Why you need a SEO Agency now</h4>
                     <div class="ms_subtitle">November 1st, 2017</div>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                  </div>
               </div>

                <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="img_container">
                         <img src="../assets/img/related-service-2-700x441.jpg" alt="">
                     </div>
                     <h4>Why you need a SEO Agency now</h4>
                     <div class="ms_subtitle">November 1st, 2017</div>
                     <p>Nesciunt magnam exercitationem obcaecati officia quos officiis vel excepturi, facilis nihil numquam et!</p>
                  </div>
               </div>

          </div>
        </div>
         <div class="ms_bottom">
           <a href="">See our work</a>
        </div>  
     </div>
   </section>
</template>

<script>
export default {
     name: 'OurNews',

}

</script>

<style lang="scss" scoped>

.main_title{
   margin-bottom: 80px;
  }

.ms_card{
   background-color: beige;
   padding: 0;

      h4{
         margin-top: 1.5rem;
         margin-bottom: 0.3rem;
         color: orange;
      }

      .ms_subtitle{
        font-size: 0.9rem ;
        margin-bottom: 0.5rem;


      }

      p{
         margin-bottom: 2rem;
      }

   }

  .ms_bottom{
    margin: 50px 0;
    text-align: center;
  }  


</style>