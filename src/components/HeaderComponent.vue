<template>
  <header>
        <div class="ms_container">
            <div class="top_header d-flex justify-content-between d-flex align-items-center">
                <div class="logo">
                  <img src="../assets/img/logo_seo_w_2x.png" alt="logo" />
                </div>
                <nav class="d-flex align-items-center">
                    <ul class="d-flex">
                       <NavList 
                          v-for="navLink, index in navLinks" :key="index" :item="navLink"
                       />
                    </ul>
                    <div class="ms_button">
                      <a href="#">get in touch now</a>
                    </div>
                </nav>
            </div>
            <div class="ms_jumbotron">
              <div class="row row-cols-2">
                <div class="col">
                  <h2>SEM Campaign Made simple With Avada</h2>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, sunt vero! Delectus est aspernatur magnam illum! </p>
                  <div class="buttons">
                    <span class="ms_button">buy avada now</span>
                    <span class="ms_button blue">contact us</span>
                  </div>
                </div>
              </div>

            </div>
        </div>       
  </header>
</template>

<script>
import NavList from './NavList.vue'

export default {
    name: "HeaderComponent",
    components: {
          NavList
      },
      data() {
        return {
            navLinks: [
                {
                    text: 'Home',
                    url: '#',
                    current: true,
                    apply: false
                },
                {
                    text: 'Who We Are',
                    url: '#',
                    current: false,
                    apply: false
                },
                {
                    text: 'What We Do',
                    url: '#',
                    current: false,
                    apply: false
                },
                {
                    text: 'Where We Work',
                    url: '#',
                    current: false,
                    apply: false
                },
                {
                    text: 'Carrers',
                    url: '#',
                    current: false,
                    apply: true
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                    apply: false
                },
             ],
         };
       }
    }
</script>

<style lang="scss" scoped>
 @import '../assets/scss/vars.scss';


header{
      background-image: url(../assets/img/1-hero-image.png);
      background-size: cover;
      background-repeat: no-repeat;
      background-position-x: 50%;
      background-position-y: 0;
      min-width: 1500px;
      color: $text-second;
      margin-right: -12px;

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
                    
                    .ms_button{
                      margin-left: 10px;
                    }
                 }
              }

          .ms_jumbotron{
          padding: 240px 0;

                p{
                  margin: 20px 0 40px 0;
                  padding-right: 1.5rem;
                  text-align: start;
                }
              
                .buttons{
                    .ms_button{

                        margin-right: 1.3rem;
                        letter-spacing: 2px;
                        padding: 0.8rem 2.3rem;
                        border-radius: 30px;
                    }

                    .ms_button.blue{
                      background-color: $text-blue;
                    }
                  }
              }
     }
</style>