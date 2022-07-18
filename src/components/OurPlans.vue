<template>
   <section id="our-plans" class="row mb-0">
      <div class="ms_container">
        <div class="main_title">
           <h3>Our Plans</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-4">

                 <div class="col" v-for="cardItem, index in cardItems" :key="index">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <h5>{{cardItem.offer}}</h5>
                     <div class="price_container d-flex">
                        <div class="dollar_symbol">$</div>
                        <div class="main_number">{{cardItem.price}}</div>
                        <div class="cents_time d-flex flex-column justify-content-around">
                            <div class="cents">99</div>
                            <div class="time">monthly</div>
                        </div>
                     </div>
                     <p>{{cardItem.projects}} Projects</p>
                     <p>{{cardItem.storage}} storage</p>
                     <p>Umlimited users</p>
                     <div :class="{'bg_orange': cardItem.isActive}" class="ms_button ">
                        <a href="#">Start today</a>
                     </div>
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
      data(){
         return{

            cardItems: [
               {
                  offer: 'Standard',
                  price: '19',
                  projects: '5',
                  storage: '5GB',
                  isActive: false,
               },
                  {
                  offer: 'Standard',
                  price: '29',
                  projects: '10',
                  storage: '5GB',
                  isActive: false,
               },
                  {
                  offer: 'Standard',
                  price: '39',
                  projects: '5',
                  storage: '15GB',
                  isActive: true,
               },
                  {
                  offer: 'Standard',
                  price: '59',
                  projects: 'Unlimited',
                  storage: 'Unlimited',
                  isActive: false,
               },
            ],
        };
   }

}

</script>

<style lang="scss" scoped>
 @import '../assets/scss/vars.scss';

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

      p{
          color: $text-second;
         }
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
                color: $text-deep-blue;
           }

           .cents_time{

                .cents{
                     font-weight: bolder;
                     color: $text-deep-blue;
                }

                .time{
                     font-size: 0.6rem;
                     font-style: oblique;
                } 
           }
        }  

           p{
            margin-bottom: 30px;
            color: $subtext-color;
             }

          .ms_button{
            padding: 0.6rem 1.3rem;
            border: 1px solid $subtext-color;
             color: $subtext-color;
            background-color: inherit;
          }

          .ms_button.bg_orange{
            background-color: $text-special;
            color: white;
            border: 0px solid $subtext-color;
          }
   }
}

</style>