<template>
   <section id="our-plans" class="row mb-0">
      <div class="ms_container">
        <div class="main_title">
           <h3>Our Plans</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-4">

                <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <h5>Standard</h5>
                     <div class="price_container d-flex">
                        <div class="dollar_symbol">$</div>
                        <div class="main_number">19</div>
                        <div class="cents_time d-flex flex-column justify-content-around">
                            <div class="cents">99</div>
                            <div class="time">monthly</div>
                        </div>
                     </div>
                     <p>5 Projects</p>
                     <p>5 GB storage</p>
                     <p>Umlimited users</p>
                     <div class="ms_button">
                        <a href="#">Start today</a>
                     </div>
                  </div>
               </div>

               <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <h5>Standard</h5>
                     <div class="price_container d-flex">
                        <div class="dollar_symbol">$</div>
                        <div class="main_number">19</div>
                        <div class="cents_time d-flex flex-column justify-content-around">
                            <div class="cents">99</div>
                            <div class="time">monthly</div>
                        </div>
                     </div>
                     <p>5 Projects</p>
                     <p>5 GB storage</p>
                     <p>Umlimited users</p>
                     <a href="#">Start today</a>
                  </div>
               </div>

               <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <h5>Standard</h5>
                     <div class="price_container d-flex">
                        <div class="dollar_symbol">$</div>
                        <div class="main_number">19</div>
                        <div class="cents_time d-flex flex-column justify-content-around">
                            <div class="cents">99</div>
                            <div class="time">monthly</div>
                        </div>
                     </div>
                     <p>5 Projects</p>
                     <p>5 GB storage</p>
                     <p>Umlimited users</p>
                     <a href="#">Start today</a>
                  </div>
               </div>

               <div class="col">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <h5>Standard</h5>
                     <div class="price_container d-flex">
                        <div class="dollar_symbol">$</div>
                        <div class="main_number">19</div>
                        <div class="cents_time d-flex flex-column justify-content-around">
                            <div class="cents">99</div>
                            <div class="time">monthly</div>
                        </div>
                     </div>
                     <p>5 Projects</p>
                     <p>5 GB storage</p>
                     <p>Umlimited users</p>
                     <a href="#">Start today</a>
                  </div>
               </div>


          </div>
        </div>  
     </div>
   </section>
</template>

<script>
export default {
      name: 'OurPlans',

}

</script>

<style lang="scss" scoped>

#our-plans{
      background-image: url(../assets/img/background1.jpg);
      background-size: cover;
      background-repeat: no-repeat;
      background-position-x: 50%;
      background-position-y: 30%;
      min-width: 800px;
      color: white;
}

.ms_container{
  padding-bottom: 150px;
  
  .main_title{
   margin-top: 120px; 
   margin-bottom: 80px;
  }

.ms_card{
    padding: 30px 50px;
    background-color: white;
    color: black;

     .price_container{
        margin-bottom: 20px;
        margin-top: 20px;
           
           .dollar_symbol{
                padding-top: 7px;
                font-weight: bolder;
           }
           
           .main_number{
                font-size: 2.5rem;
                font-weight: bolder;
                color: blue
           }

           .cents_time{

                .cents{
                     font-weight: bolder;
                     color: blue
                }

                .time{
                     font-size: 0.6rem;
                     font-style: oblique;
                } 

           }

          
        }  

           p{
            margin-bottom: 30px;
             }

          .ms_button{
            padding: 0.6rem 1.6rem;
            border: 1px solid black;
            color: black;
            background-color: inherit;
          }
   }
}

</style>