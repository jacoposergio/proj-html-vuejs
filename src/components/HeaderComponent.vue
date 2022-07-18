<template>
  <header>
        <div class="ms_container">
            <div class="top_header d-flex justify-content-between">
                <div class="logo">
                  <img src="../assets/img/logo_seo_w_2x.png" alt="logo" />
                </div>
                <nav>
                    <ul class="d-flex">
                        <li>
                            element
                        </li>
                        <li>
                            element
                        </li>
                        <li>
                              element
                        </li>
                        <li>
                              element
                        </li>
                        <li>
                            element
                        </li>
                        <li>
                              element
                        </li>
                          <li>
                              element
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="ms_jumbotron">
              <div class="row row-cols-2">
                <div class="col">
                  <h2>SEM Campaign made simple With Avada</h2>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, sunt vero! Delectus est aspernatur magnam illum! </p>
                  <div class="buttons">
                    <span>element sono un btn</span>
                    <span>bella pevvoi</span>
                  </div>
                </div>
              </div>

            </div>
        </div>       
  </header>
</template>

<script>
export default {
     name: 'HeaderComponent',

}
</script>

<style lang="scss" scoped>


header{
      background-image: url(../assets/img/1-hero-image.png);
      background-size: cover;
      background-repeat: no-repeat;
      background-position-x: 50%;
      background-position-y: 0;
      min-width: 800px;
       color: white;

  .top_header{
    padding-top: 40px;

       .logo{

            
            img{
              width: 130px;
            }
         }

          nav{
              
                ul{

                
                     li{
                         font-size: 1.2rem;
                         margin-right: 30px;
                     } 
                 }
          }
  }

.ms_jumbotron{

  padding: 240px 0;

  p{
    padding-right: 1.5rem;
    text-align: start;
  }

}






}



</style>