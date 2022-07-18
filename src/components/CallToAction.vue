<template>
   <section id="call_to_action" class="row mb-0">
      <div class="overlay"></div> 
      <div class="ms_container">
        <div class="main_title">
           <h3>Start your free consultation</h3>
           <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. molestias iure repellat neque.molestias iure repellat neque.</p>
           <div class="ms_button">
             <a href="">contact us now</a>
           </div>  
        </div>
       
      
      </div>
   </section>
</template>

<script>
export default {
      name: 'CallToAction',

}

</script>

<style lang="scss" scoped>

#call_to_action{
      background-image: url(../assets/img/CTA-seo-1.jpg);
      background-size: cover;
      background-repeat: no-repeat;
      background-position-x: 50%;
      background-position-y: 50%;
      min-width: 800px;
      color: white;
      position: relative;
      z-index: -2;

             .overlay{
              position: absolute;
              width: 100%;
              height: 100%;
              top: 0;
              right: 0;
              background-color: black;
              z-index: -1;
              opacity: 0.5;

             }
            .main_title{
              padding: 100px 0;
              z-index: 3;
               margin: 50px auto;

                  p{
                     margin-top: 20px;
                  }
            }

            .ms_button{
               margin-top: 15px;
            }

      
}

</style>