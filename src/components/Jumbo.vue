<script>
import { FontAwesomeIcon} from '@fortawesome/vue-fontawesome'

export default {
  data() {
    return {
      imageUrl: "../assets/cheeky-african-american-man-party-outfit-winking-camera-smiling-standing-against-red-backg.jpg"
    }
  },
  components:{
    "font-awesome-icon":FontAwesomeIcon

  }
};
</script>

<template>
  <div class="jumbotron">
    <div class="nav">
      <!-- <font-awesome-icon icon="fa-solid fa-user-secret" /> -->
      <!-- <a>Contact</a> -->
      <div>
        
      </div>
      <div class="tab-1">
        <div class="form-2">
          <form action="" method="post">
            <input type="text" placeholder="What are you looking for ...">
            <button><font-awesome-icon icon="fa-solid fa fa-search" color="white"/> </button>
          </form>
        </div>
        <div>
          <a><font-awesome-icon icon="fa-solid fa-shopping-cart" color="white"/></a>
          <a><font-awesome-icon icon="fa-solid fa-heart" color="white"/></a>
          <!-- <a>Login</a> -->
          <a>Register/Login</a>
          <a>Account</a>
          <a>Home</a>
          
        </div>
    
        
      </div>
     
     
    </div>
 
  </div>
  <div class="hero">
    <h2>Don't Miss</h2>
    <h1>Mystery  Deals</h1>
    <p>Online Only</p>
    <button>Shop Now</button>
  </div>
 
  <div class="brands">
    <div><img src="@/assets/yeezy.jpg"/></div>
    <div><img src="@/assets/gucci.png"/></div>
    <div><img src="@/assets/yeezy.jpg"/></div>
    <div><img src="@/assets/yeezy.jpg"/></div>
    <div><img src="@/assets/yeezy.jpg"/></div>
    <div><img src="@/assets/yeezy.jpg"/></div>
    <div><img src="@/assets/yeezy.jpg"/></div>
   
  </div>

  <div class="trendy">
    <div class="big-1">

    <img class="big-1" src="@/assets/banner-1.jpg"/>
     
    </div>
 
   
    <div class="">
      <div class="mini">
        <div> <img src="@/assets/banner-2.jpg"/></div>
        <div><img src="@/assets/banner-3.jpg" alt=""/></div>

       
        

      </div>
  
      
    </div>
    
  </div> 
  <div class="tag">
    <h2>Trending Products</h2>

  </div>
  
  <div class="section-1">
    <div>
      <img src="@/assets/bag2.jpg" alt="">
     

    </div>
    <div>
      <img src="@/assets/bag3.jpg" alt="">

    </div>
    <div>
      <img src="@/assets/shoe1.jpg" alt="">

    </div>
    <div>
      <img src="@/assets/woman1.jpg" alt="">

    </div>
    <div>
      <img src="@/assets/man1.jpg" alt="">

    </div>
   
  </div>
  <!-- <div class="vid">
    <button class="vid1"></button>
    <div class="container1">
      <h3>Product Demo</h3>
      <a href="" class="vid1"></a>
    </div>
  </div> -->
  <div class="main1"></div>
  <div class="title1">
    <h3>New Arrivals</h3>
      
  </div>
  <div class="new-arrival">
    <div><img src="@/assets/woman1.jpg" alt=""></div>
    <div><img src="@/assets/woman2.jpg" alt=""></div>
    <div><img src="@/assets/shoe1.jpg" alt=""></div>
    <div><img src="@/assets/man1.jpg" alt=""></div>
    <div><img src="@/assets/bag2.jpg" alt=""></div>
    <div><img src="@/assets/bag3.jpg" alt=""></div>
    <div><img src="@/assets/woman2.jpg" alt=""></div>
    <div><img src="@/assets/shoe1.jpg" alt=""></div>
  
  </div>
  <div class="load1">
    <button >Load More</button>
  </div>
  <div class="socials">
    <div class="social-1">
      <h4>Our Socials</h4>
      <!-- <font-awesome-icon icon="fa-solid fa-user-secret "/> -->
      <a href=""><img src="@/assets/facebook.png" alt=""></a>
      <a href=""><img src="@/assets/twitter-1.png" alt=""></a>
      <a href=""><img src="@/assets/instagram.png" alt=""></a>
      <a href=""><img src="@/assets/pinterest.png" alt=""></a>
      <a href=""><img src="@/assets/youtube.png" alt=""></a>
    </div>
    <div class="horizon"></div>
    <div style="margin: 25px; align-items: center;">
      <h4 style="margin:8px;font-weight: bolder;text-align: center;color:maroon;">Get Latest Deal</h4>
      <p style="font-size:15px;text-align: center;margin:10px;">and <br> Recieve 30% off on first shopping</p>
      <form class="form-1" action="" method="post">
        <input type="text" id="lname" name="lastname" placeholder="Subscribe to News Letter">
        
      </form>
    </div>
  </div>
  <div class="footer">
    <div>
      <h2>Freedom</h2>
      <br>
      <p style="font-size:small">Praesent dapibus, neque id cursus ucibus,<br> tortor neque egestas augue,<br>
         eu vulputate magna eros eu erat. Aliquam erat volutpat.<br> Nam dui mi, tincidunt quis, accumsan <br> porttitor, facilisis luctus, metus.</p>
      <br>  
      <p style="font-size:small;">Need to Speak to us ? Call us 24/7 or WhatsApp Us on</p>
      <p style="color:maroon;">+254708520548</p>

    </div>
    <div>
      <h2>Account</h2>
      <br>
      <ul>
        <li><a href="">Sign In</a></li>
        <li><a href="">Register</a></li>
        <li> <a href="">Orders</a></li>
      </ul>
    </div>
    <div>
      <h2>Customer Services</h2>
      <br>
      <ul>
        <li><a href="">Payment Methods</a></li>
        <li><a href=""> Money-back guarantee!</a></li>
        <li> <a href="">Returns</a></li>
        <li> <a href="">Shipping</a></li>
        <li><a href="">Privacy Policy</a></li>
        <li> <a href="">Terms and conditions</a></li>
        
      </ul>
    </div>
    <div>
      <h2>Information</h2>
      <br>
      <ul>
        <li><a href="">About Molla</a></li>
        <li><a href=""> How to shop on Molla</a></li>
        <li> <a href="">FAQ</a></li>
        <li> <a href="">Contact us</a></li>
        <li><a href="">Log in</a></li>
         
  
      </ul>   
    </div>
    <div>
      <h2>Payment Methods</h2>
    </div>

  </div>
 
  <div class="lasty">
    <p style="font-size: small;">Copy Right 2023 | Freedom Store | All Right Reserved <a href="#">Terms of use</a> | Privacy Policy </p>
  </div>
</template>

<style scoped>
.lasty{
  text-align: center;
}
.footer{
  background-color:black;
  color:white;
  padding:80px;
  display: flex;
  flex-direction: row;
  justify-content:space-around;
}
.footer h2{
  font-size:2 rem;
}
.footer ul{
  text-align: left;
  margin: 0;
  padding: 0; 
 
}
.footer ul li{

  list-style-type: none;
  text-align: left;
  line-height: 1.6;

  
}
.footer ul li a{
  text-decoration:none;
  color:white;
  outline: none;

}
.footer ul li a:hover{
  text-decoration:none;
  color:maroon;
  outline: none;

}
.socials{
  display: flex;
  justify-content: center;
  padding:30px;
  
  
}
.social-1{
  align-items: center;
  margin:25px;

}
.socials h4{
  font-weight: bolder;
  margin:15px;
  text-align:center;
  color:maroon;
}
.social-1 a img{
  margin:7px;
  height: 32px;

}

.social-1 a img:hover{
  margin:7px;
  height: 32px;
  color: maroon;

}
.horizon{
  border-left: 1px solid black;
  height: 160px;
  margin:10px;
}
.load1{
  display: flex;
  justify-content: center;
  margin: 20px;


}
.form-1 input{
  border-color:black;
  border-width: 1px;
  border-radius: 28px;
  padding:10px 45px;
  outline: none;

}
.form-1 input:hover{
  border-color:maroon;
  border-width: 1px;
  border-radius: 28px;
  padding:10px 45px;
  outline: none;

}
.load1 button{
  padding:10px 35px;
  color:maroon;
  background-color: white ;
  border-radius: 22px;
  border-width: 1px ;
  border-color: black;

}
.load1 button:hover{
  background-color: maroon;
  color:white;
  border-color: none;
}
.main1{
  margin-top:30px;
}
.title1{
  color:maroon;
  font-family:poppins;
  font-weight:bolder;
  text-align: center;
  margin-top:25px;
  font-size:x-large;
  position: relative;
  align-items: center;
  justify-content: center;
}
.new-arrival{
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
}
.new-arrival div{
  flex-basis:25%;
}
.new-arrival div img{
  margin:15px;
  
}
.vid{
  background-image: url('../assets/bg-2.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 50%;
  height: 90vh;
  margin-top:40px
}
.container{
  /* display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column; */
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.container1{
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); 
}
.vid1{
  width: 5.4rem;
  height: 5.4rem;
  font-size: 1.6rem;
  line-height: 1;
  background-color: #fff;
  border-radius: 50%;
  box-shadow: 0 0 0 1.5rem hsla(0,0%,100%,.2);
  transition: all .35s ease;


}
.section-1{
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.section-1 div img{
  margin:10px;
}
.tag{
  color:black;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight:1200;
  text-align: center;
  margin:20px;
  font-size:x-large;
  position: relative;
  align-items: center;
  justify-content: center;
}
.trendy{
  display:flex;
  align-items: center;
  justify-content:center;
  /* align-items: center; */
}
.mini{
  display:flex;
  flex-direction: column;
  justify-content: space-between;
}
.mini img{
  margin:10px;
}


.jumbotron{
    background-image: url('../assets/cheeky-african-american-man-party-outfit-winking-camera-smiling-standing-against-red-backg.jpg');
    background-size: cover;
    height: 100vh;
    width: 100vw;
    /* background-attachment: fixed;  */
}
.brands{
  color:black;
  margin:55px;
  display: flex;
  justify-content:space-around;
  align-content: center;
 

}
.brands div{
  border-width: 2px;
  border-color: black;
 
}
.brands img{
  width:80px;
  height:80px;
  /* background-color: inherit;
  border: 1px solid maroon;
  border-radius: 100%;
  border-spacing: 20px; */

}
.brands img:hover{
  width:80px;
  height:80px;
  background-color: inherit;
  border: 1px solid maroon;
  border-radius: 100%;
  border-spacing: 20px;
}
div .nav a{
  margin:20px 20px 20px 40px;
  color:white;
  align-items: center;
  font-size:1 rem;
  float:right;
  text-align: center;
  /* padding: 8px 13px; */
}
.hero{
  text-align: center;
  position: absolute;
  top: 50%;
  left: 70%;
  transform: translate(-50%, -50%);
  color: white;
  /* border-color: white;
  border-width: 2px;
  border-style: double; */
/*  
  padding:30px; */
  

}
.hero h1{
  font-size: 100px;
  font-weight:900;
  font-family: cursive;
  overflow: visible;
  word-wrap: normal;
}
.hero h2{
  font-size: 30px;

 
 
}
.hero p{
  margin-bottom: 3.6rem;
  font-size: 1.4rem;
}
.hero button{
  padding:15px 50px;
  border-radius: 30px;
  background-color: transparent ;
  color:white;
  border-color: white;
  border-width: 1.5px;
}

.hero button:hover{
  padding:15px 50px;
  border-radius: 30px;
  background-color: white ;
  color:red;
  border-color: white;
}
.big-1{
  /* border-style: groove;
  border:2px; */
  background-image: url('../assets/banner-1.jpg');
}
.big-1:hover{}
.tab-1{
  display: flex;
  justify-content: flex-end;
  
}
.form-2{
  margin-right: 150px;
  display: inline;
}
.form-2 form{
  display: inline;
}
.form-2 input{
  justify-content: center;
  background-color: inherit;
  color:white;
  border: none;
  border-bottom: 1.5px solid white;
  outline:none;
  width: 100%;
  padding: 12px 20px;
  margin: 8px 20px;
}
.form-2 input:focus{
  border:none;
  border-bottom: 2px solid white;
  background-color: inherit;
  padding: 12px 20px;
  margin: 8px 20px;
  outline:none;
}
.form-2 button{
  background-color: inherit;
  border:none;
  float: left;
  position: absolute;
  top: 2%;
}
.form-2 button:hover{
  background-color: inherit;
  border:none;
  float: left;
  position: absolute;
  top: 2%;
  cursor:pointer;
}




/* ul {
  list-style-type: none;
  /* margin: 0;
  padding: 0; */
  /* overflow: hidden;
  background-color: #333; */
 
/* li{
    color:white;
    display:block;  
    position: absolute;
    text-align: center;
    padding: 14px 16px;
    /* top: 8px;
    right: 16px; */
    /* font-family:popin; */
   

</style>