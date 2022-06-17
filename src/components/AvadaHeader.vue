<template>
  <header>
      <nav>
        <ul>
           <li><a href="#">We have a 95% Successful Pass Rate!</a></li>
           <li><a href="#">Give us a call to book your tuition! 1-800-555-555</a></li>
        </ul>
        
         <ul>
           <li><a href="#"><img src="../assets/images/avada-drivers-logo-2x-300x58.png" alt="footer-ad-grid"><br></a></li>
           <li><a href="#">Home</a></li>
           <li><a href="#">About</a></li>
           <li><a href="#">Prices</a></li>
           <li><a href="#">Courses</a><button type="button">Book Now</button></li>
           <li><a href="#">Locations</a></li>
           <li><a href="#">Collectibles</a></li>
           <li><a href="#">Blog</a></li>
           <li><button type="button">Book Now</button></li>  
         </ul>
      </nav>
    </header>
</template>

<script>
export default {
  name: 'AvadaHeader',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">



header {
  text-align: center;


  ul:first-child {
  background-color: #353637;
  display: flex;
  justify-content: space-between;
  
}

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
