<template>
  <header>
      <nav>
        <ul>
           <li><a href="#">Comics</a></li>
           <li><a href="#">Movies</a></li>
        </ul>
        
         <ul>
           <li><a href="#"><img alt="Avada logo" src="../assets/images/avada-drivers-logo-1x.png"></a></li>
           <li><a href="#">Characters</a></li>
           <li><a href="#">Comics</a></li>
           <li><a href="#">Movies</a></li>
           <li><a href="#">Tv</a></li>
           <li><a href="#">Games</a></li>
           <li><a href="#">Collectibles</a></li>
           <li><a href="#">Videos</a></li>
           <li><a href="#">Fans</a></li>
           <li><a href="#">News</a></li>
           <li><a href="#">Shop</a></li>
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


  ul {
    list-style-type: none;
    margin: 20px 0;
    text-align: center;
    
    

    li {
      display: inline-block;
      padding: 10px;
      

      a {
        text-decoration: none;
        color: #1C1C1C;
        text-transform: uppercase;
        font-size: 0.7em;

        img {
          text-align: start;
        }
        

        &:hover {
          color: #0082F9;
        }

        &:active {
          background-color: #0082F9;
        }
      }

    }
  }
}

</style>
