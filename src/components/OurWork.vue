<template>
   <section id="our-work">
     <div class="ms_container">
        <div class="main_title">
           <h3>Our Work</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
        </div>
        <div class="cards_container">
          <div class="row g-3 row-cols-3">

                 <div class="col" v-for="cardItem, index in cardItems" :key="index">
                  <div class="d-flex flex-column align-items-center">
                     <img :src="require(`../assets/img/${cardItem.img}.jpg`)" :alt="cardItem.title">
                  </div>
               </div>

          </div>
        </div> 
        <div class="ms_button">
          <a href="">view our work</a>
        </div>
     </div>
   </section>
</template>

<script>
export default {
      name: 'OurWork',
        data(){
      return{

         cardItems: [
            {
             title: 'image of a desktop',
             img: 'case-study-gallery-3-1-1200x900'
           },
            {
             title: 'image of a pc monitor',
             img: 'case-study-gallery-2-800x600'
           },
            {
             title: 'image of a smartphone',
             img: 'case-study-gallery-1-1-1200x900'
           },
            {
             title: 'image of a graphic',
             img: 'case-study-gallery-4-1-1200x900'
           },
            {
             title: 'image of a graphic 2',
             img: 'case-study-gallery-5-1-1200x900'
           },
            {
             title: 'image of a graphic 3',
             img: 'case-study-gallery-6-1-1200x900'
           },
         ],
      };
    }
 }
</script>

<style lang="scss" scoped>

.ms_container{
   text-align: center;
        
        .main_title{
        margin-bottom: 80px;
        }

        .ms_button{
          margin: 80px 0 100px 0;
        }
  }
</style>