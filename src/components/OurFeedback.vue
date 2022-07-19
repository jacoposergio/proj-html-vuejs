<template>
   <section id="our-feedback">
    <div class="ms_container bottom_line">
      <div class="main_title">
          <h3>What Our Clients Say</h3>
          <div class="img_container d-flex justify-content-center">
              <img src="../assets/img/testimonials-2.jpg" alt="luis de salvo image">
          </div>
          <p class="ms_quote">Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
          <div class="author"><span>Luis Desalvo, </span>CREO TECH</div>
          <div class="dots d-flex justify-content-center">
            <span class="circle"></span> <span class="circle blank"></span>
          </div>
      </div>
    </div> 
    <div class="ms_container">
      <div class="partners-logo">
        <div class="row g-3 row-cols-4">

           <div class="col" v-for="cardItem, index in cardItems" :key="index">
            <div class="logo-container d-flex justify-content-center">
              <img :src="require(`../assets/img/${cardItem.img}.png`)" :alt="cardItem.title">
            </div>
          </div>
        
        </div>
      </div>
    </div>  
   </section>
</template>

<script>
export default {
      name: 'OurFeedback',
         data(){
      return{

         cardItems: [
            {
             title: 'Avada Health',
             img: 'clients_partner_4-200x202'
           },
            {
             title: 'Avada University',
             img: 'clients_partner_6-200x202'
           },
            {
             title: 'Avada VET',
             img: 'clients_partner_3-200x202'
           },
            {
             title: 'Awada Law',
             img: 'clients_partner_2-200x202'
           },
         ],
      };
    }
 }

</script>

<style lang="scss" scoped>
 @import '../assets/scss/vars.scss';

#our-feedback{
   background-color: $text-second;

      .ms_container.bottom_line{
        border-bottom: 1px solid $thin-line;
  
              .main_title{
                 padding-top: 100px;
                    .img_container{
                      margin: 2.5rem 0 2rem 0;
                  
                          img{
                            border-radius: 50%;
                            width: 130px;
                          }
                       }
      
              .dots{
                padding-bottom: 50px;
                
                    .circle{
                        display: block;
                        background-color: $text-first;
                        width: 12px;
                        height: 12px;
                        border-radius: 50%;
                        margin-top: 1.5rem;
                      }
              
                    .circle.blank{
                        border: 1px solid $text-first;
                        background-color: $text-second;
                        margin-left: 5px;
                     }
                  }
             }
         }
  
      .logo-container{
       
            img{
                width: 100px;
                margin: 50px 0;
            }
         }
   }
</style>