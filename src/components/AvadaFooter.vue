<template>
    
      <section>
           <div>
               <img src="../assets/images/avada-drivers-logo-2x-300x58.png" alt="footer-ad-grid">
               <p>Avada Driving School the right choice for experienced drivers looking foa a refresher course. or the brand new driver wanting to pass first time.</p>
           </div> 
          <div>
              <nav>
                  <ul>
                      <h3>Courses</h3>
                      <li><a href="#"></a>12345 North Main Street, New York, NY 555555</li>
                      <li><a href="#"></a>1.800.555.6789</li>
                      <li><a href="#"></a>info@your-domain.com</li>
                      <li><a href="#"></a>Theme.Fusion.com</li>
                 </ul>
             </nav>  
         </div>
         <div>
          <nav>
              <ul>
                  <h3>Contact Details</h3>
                  <li><a href="#"></a>Pass Plus</li>
                  <li><a href="#"></a>Intensive Couse</li>
                  <li><a href="#"></a>Auutomatic</li>
                  <li><a href="#"></a>Instructor Training</li>
              </ul>
          </nav>
          </div>
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
      display: flex;
      justify-content: space-between;

  ul {
    list-style-type: none;
    margin: 20px 0;
    text-align: center;
    

    li {
      display: inline-block;
      padding: 10px;
      

      a {
        text-decoration: none;
        color: #8295A0;
        text-transform: uppercase;
        font-size: 0.7em;

        img {
          text-align: start;
        }
        

        &:hover {
          color: #7ABC64;
        }

        &:active {
          background-color: #7ABC64;
        }
      }

    }
  }
}

  
     
  
 
  </style>