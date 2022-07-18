<template>
  <footer>
    <div class="ms_container d-flex flex-column align-items-center">
      <div class="logo_container">
        <img src="../assets/img/logo_seo_2x.png" alt="Seo logo">
      </div>
        <ul class="footer_links d-flex justify-content-between">
          <li>
            <a href="Home">home</a>
          </li>
           <li>
            <a href="Who we are">ciao</a>
          </li>
           <li>
             <a href="Who we are">bella</a>
          </li>
           <li>
            <a href="Who we are">tori</a>
          </li>
           <li>
             <a href="Who we are">rocce</a>
          </li>
        </ul>
         <ul class="site_info d-flex justify-content-center">
          <li>
            CPyright |
          </li>
           <li>
            Avada team |
          </li>
           <li>
           aiutos |
          </li>
           <li>
            link
          </li>
           <li>
            link
          </li>
        </ul>
         <ul class="social_links d-flex justify-content-center">
          <li>
            link
          </li>
           <li>
            link
          </li>
           <li>
            link
          </li>
           <li>
            link
          </li>
           <li>
            link
          </li>
        </ul>
    </div>
  </footer>
</template>

<script>
export default {
     name: 'FooterComponent',

}
</script>

<style lang="scss" scoped>

.ms_container{
    .logo_container{
    
          img{
            width: 170px;
            margin: 80px 0 50px 0;
          }
    }

    ul{
      width: 100%;
    }

       .footer_links{
        margin-bottom: 50px ;      

     }

   .site_info{
    margin-bottom: 30px;

       li{
        margin-right: 1rem;
       }

    }

      .social_links{

      li{
      margin-right: 1rem;
      }

  }
}

</style>