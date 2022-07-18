<template>
   <section id="our-news">
     <div class="ms_container">
        <div class="main_title">
           <h3>Our News</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-4 row-cols-3">

                <div class="col" v-for="cardItem, index in cardItems" :key="index">
                  <div class="ms_card d-flex flex-column align-items-center">
                     <div class="img_container">
                         <img :src="require(`../assets/img/${cardItem.img}.jpg`)" :alt="cardItem.imgTitle">
                     </div>
                     <h4>{{cardItem.title}}</h4>
                     <div class="ms_subtitle">{{cardItem.subtitle}}</div>
                     <p>{{cardItem.content}}</p>
                  </div>
               </div>
            
          </div>
        </div>
         <div class="ms_button">
           <a href="">go to news</a>
        </div>  
     </div>
   </section>
</template>

<script>
export default {
     name: 'OurNews',
     data(){
         return{

            cardItems: [
               {
               img: 'related-service-2-700x441',
               title: 'Why you need a SEO Agency now',
               subtitle: 'November 1st, 2017',
               content: 'Nesciunt magnam exercitationem obcaecati officia , facilis nihil numquam et quos officiis vel excepturi, obcaecati officia facilis nihil numquam et!',
               imgTitle: 'image of a office'
               },
               {
               img: 'related-service-4-700x441',
               title: 'SEO tips for your Startup',
               subtitle: 'November 1st, 2017',
               content: 'Nesciunt magnam exercitationem obcaecati officia quo facilis nihil numquam ets officiis vel excepturi, facilis nihil numquam et!',
               imgTitle: 'image of a monitor'
               },
               {
               img: 'blog-post-6-700x441',
               title: 'Image Optimization For Your Site',
               subtitle: 'November 1st, 2017',
               content: 'Nesciunt magnam exercitationem obcaecati officia  quos officiis vel numquam ets excepturi, facilis quos officiis vel excepturi, facilis nihil numquam et!',
               imgTitle: 'image of a tablet'
               },
            ],
        };
   }

}

</script>

<style lang="scss" scoped>
 @import '../assets/scss/vars.scss';

#our-news{
   .ms_container{
      text-align: center;
      
         .main_title{
            margin-bottom: 80px;
         }
         
         .ms_card{
            padding: 0;
         
               h4{
                  margin-top: 1.5rem;
                  margin-bottom: 0.3rem;
                  color: $text-special;
               }
         
               .ms_subtitle{
               font-size: 0.9rem ;
               margin-bottom: 0.5rem;
               color: $subtext-color;
               }
         
               p{
                  margin-bottom: 2rem;
                  color: $subtext-color;
               }
         
            }
   
         .ms_button{
            margin-top: 50px;
            text-align: center;
         }  
   }
}


</style>