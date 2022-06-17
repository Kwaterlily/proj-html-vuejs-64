<template>
    
      <section>
           <div>
               <img src="../assets/images/avada-drivers-logo-2x-200x39.png" alt="footer-ad-grid">
           </div> 
          <div>
              <p>Avada Driving School the right choice for experienced drivers looking foa a refresher course. or the brand new driver wanting to pass first time.</p>
         </div>   
          <nav>
              <ul>
                  <li><a href="#"></a>12345 North Main Street, New York, NY 555555</li>
                  <li><a href="#"></a>1.800.555.6789</li>
                  <li><a href="#"></a>info@your-domain.com</li>
                  <li><a href="#"></a>Theme.Fusion.com</li>
              </ul>
              <ul>
                  <li><a href="#"></a>Pass Plus</li>
                  <li><a href="#"></a>Intensive Couse</li>
                  <li><a href="#"></a>Auutomatic</li>
                  <li><a href="#"></a>Instructor Training</li>
              </ul>
          </nav>
          <div>
              <img src="../assets/images/footer-ad-grid-400x357.png" alt="footer-ad-grid"><br>
              <button type="button">Book Now</button>
          </div>  
      </section>

  </template>
  
  <script>
  export default {
    name: 'AvadaFooter',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">

  section {
      text-align: center;
      background-image: url("../assets/images/footer-background-color.jpg");
      background-repeat: no-repeat;


      nav {


          ul {


              li {


                  a {
                    
                  }
              }
          }
      }
  
  
  }   
  
 
  </style>