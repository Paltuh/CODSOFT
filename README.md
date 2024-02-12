<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Pizza Taste Shop Website Design</title>

   <!-- font awesome cdn link  -->
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">

   <!-- custom css file link  -->
   <link rel="stylesheet" href="css/style.css">

</head>
<body>
   
<!-- header section starts  -->

<header class="header">

   <section class="flex">

      <a href="#home" class="logo">PIZZA TAASTE</a>

      <nav class="navbar">
         <a href="#home">Home</a>
         <a href="#about">About</a>
         <a href="#menu">Menu</a>
         <a href="#order">Order</a>
         <a href="#faq">CAQ</a>
      </nav>

      <div class="icons">
         <div id="menu-btn" class="fas fa-bars"></div>
         <div id="user-btn" class="fas fa-user"></div>
         <div id="order-btn" class="fas fa-box"></div>
         <div id="cart-btn" class="fas fa-shopping-cart"><span>(3)</span></div>
      </div>

   </section>

</header>

<!-- header section ends -->

<div class="user-account">

   <section>

      <div id="close-account"><span>close</span></div>

      <div class="user">
         <p><span>you are not logged in now!</span></p>
      </div>

      <div class="display-orders">
         <p>pizza-1 <span>( Rs.69/- x 2 )</span></p>
         <p>pizza 03 <span>( Rs.115/- x 1 )</span></p>
         <p>pizza 06 <span>( Rs.145/- x 4 )</span></p>
         <p>pizza 07 <span>( Rs.100/- x 1 )</span></p>
      </div>

      <div class="flex">

         <form action="" method="post">
            <h3>login now</h3>
            <input type="email" name="email" required class="box" placeholder="enter your email" maxlength="50">
            <input type="password" name="pass" required class="box" placeholder="enter your password" maxlength="20">
            <input type="submit" value="login now" name="login" class="btn">
         </form>

         <form action="" method="post">
            <h3>register now</h3>
            <input type="text" name="name" required class="box" placeholder="enter your name" maxlength="20">
            <input type="email" name="email" required class="box" placeholder="enter your email" maxlength="50">
            <input type="password" name="pass" required class="box" placeholder="enter your password" maxlength="20">
            <input type="password" name="cpass" required class="box" placeholder="confirm your password" maxlength="20">
            <input type="submit" value="register now" name="register" class="btn">
         </form>

      </div>

   </section>

</div>

<div class="my-orders">

   <section>

      <div id="close-orders"><span>close</span></div>

      <h3 class="title"> my orders </h3>

      <div class="box">
         <p>placed on : <span>06/04/2022</span> </p>
         <p>name : <span>shaikh anas</span> </p>
         <p>number : <span>1234567890</span></p>
         <p>address : <span>flat no. 123, bulding no. 2, jogeshwari, mumbai, india - 400104</span></p>
         <p>payment method : <span>cash on delivery</span></p>
         <p>your orders : <span>pizza 01 $3/- x 2, pizza 03 $2/- x 1, pizza 06 $4/- x 4, pizza 07, $2/- x 1</span></p>
         <p>total price : <span>$11/-</span></p>
         <p>payment status : <span style="color: var(--red);">pending</span> </p>
      </div>

      <div class="box">
         <p>placed on : <span>06/04/2022</span> </p>
         <p>name : <span>shaikh anas</span> </p>
         <p>number : <span>1234567890</span></p>
         <p>address : <span>flat no. 123, bulding no. 2, jogeshwari, mumbai, india - 400104</span></p>
         <p>payment method : <span>cash on delivery</span></p>
         <p>your orders : <span>pizza 01 $3/- x 2, pizza 03 $2/- x 1, pizza 06 $4/- x 4, pizza 07, $2/- x 1</span></p>
         <p>total price : <span>$11/-</span></p>
         <p>payment status : <span style="color: var(--red);">pending</span> </p>
      </div>

   </section>

</div>

<div class="shopping-cart">

   <section>

      <div id="close-cart"><span>close</span></div>

      <div class="box">
         <a href="#" class="fas fa-times"></a>
         <img src="images/pizza-1.jpg" alt="">
         <div class="content">
            <p>Veggie Paradise Pizza <span>( Rs.69/- x 2 )</span></p>
            <form action="" method="post">
               <input type="number" class="qty" name="qty" min="1" value="2" max="100">
               <button type="submit" class="fas fa-edit" name="update_qty"></button>
            </form>
         </div>
      </div>

      <div

      <div class="box">
         <a href="#" class="fas fa-times"></a>
         <img src="images/pizza-6.jpg" alt="">
         <div class="content">
            <p>Peppy Paneer Pizza <span>( Rs.130/- x 2 )</span></p>
            <form action="" method="post">
               <input type="number" class="qty" name="qty" min="1" value="2" max="100">
               <button type="submit" class="fas fa-edit" name="update_qty"></button>
            </form>
         </div>
      </div>

      <div class="box">
         <a href="#" class="fas fa-times"></a>
         <img src="images/pizza-7.jpg" alt="">
         <div class="content">
            <p>Deluxe Extravaganza Pizza <span>( Rs.145/- x 1 )</span></p>
            <form action="" method="post">
               <input type="number" class="qty" name="qty" min="1" value="1" max="100">
               <button type="submit" class="fas fa-edit" name="update_qty"></button>
            </form>
         </div>
      </div>

      <a href="#order" class="btn">Order now</a>

   </section>

</div>

<div class="home-bg">

   <section class="home" id="home">

      <div class="slide-container">

         <div class="slide active">
            <div class="image">
               <img src="E:\Mtech Geoinformatics and Surveying Technology_Symbiosis_2023_25\2ND SEMESTER\CodfSoft Internship\Web Page Development\Landing Page\Mascarpone Pizza.jpg" alt="">
            </div>
            <div class="content">
               <h3>Frankfurter Pizza</h3>
               <div class="fas fa-angle-left" onclick="prev()"></div>
               <div class="fas fa-angle-right" onclick="next()"></div>
            </div>
         </div>

         <div class="slide">
            <div class="image">
               <img src="E:\Mtech Geoinformatics and Surveying Technology_Symbiosis_2023_25\2ND SEMESTER\CodfSoft Internship\Web Page Development\Landing Page\Pizza_Taste2.jpg" alt="">
            </div>
            <div class="content">
               <h3>Mushroom Delight Pizza</h3>
               <div class="fas fa-angle-left" onclick="prev()"></div>
               <div class="fas fa-angle-right" onclick="next()"></div>
            </div>
         </div>

         <div class="slide">
            <div class="image">
               <img src="E:\Mtech Geoinformatics and Surveying Technology_Symbiosis_2023_25\2ND SEMESTER\CodfSoft Internship\Web Page Development\Landing Page\Frankfuter Pizza.jpg" alt="">
            </div>
            <div class="content">
               <h3>Mascarpone And Mushrooms</h3>
               <div class="fas fa-angle-left" onclick="prev()"></div>
               <div class="fas fa-angle-right" onclick="next()"></div>
            </div>
         </div>

      </div>

   </section>

</div>

<!-- about section starts  -->

<section class="about" id="about">

   <h1 class="heading">about us</h1>

   <div class="box-container">

      <div class="box">
         <img src="E:\Mtech Geoinformatics and Surveying Technology_Symbiosis_2023_25\2ND SEMESTER\CodfSoft Internship\Web Page Development\Landing Page\making pizza.jpg" alt="">
         <h3>Made with Care & Love</h3>
         <p>"Crafted with passion and baked to perfection, our pizzas are made with love to delight our cherished customers with every delicious slice."</p>
         <a href="#menu" class="btn">our menu</a>
      </div>

      <div class="box">
         <img src="E:\Mtech Geoinformatics and Surveying Technology_Symbiosis_2023_25\2ND SEMESTER\CodfSoft Internship\Web Page Development\Landing Page\Delivery Service.jpg" alt="">
         <h3>30 minutes delivery</h3>
         <p>
"Experience prompt satisfaction with our swift delivery service – piping hot pizzas at your doorstep within 30 minutes, ensuring a delectable and timely dining experience for our valued customers."</p>
         <a href="#menu" class="btn">our menu</a>
      </div>

      <div class="box">
         <img src="E:\Mtech Geoinformatics and Surveying Technology_Symbiosis_2023_25\2ND SEMESTER\CodfSoft Internship\Web Page Development\Landing Page\sharing pizza.jpg" alt="">
         <h3>Share with your friends and family</h3>
         <p>
"Indulge in the ultimate pizza experience with us – order now and share the joy of delicious slices with your friends, delivered right to your doorstep!"</p>
         <a href="#menu" class="btn">our menu</a>
      </div>

   </div>

</section>

<!-- about section ends -->

<!-- menu section starts  -->

<section id="menu" class="menu">

   <h1 class="heading">our menu</h1>

   <div class="box-container">

      <div class="box">
         <div class="price">Rs.<span>69</span>/-</div>
         <img src="images/pizza-1.jpg" alt="">
         <div class="name">Veggie Paradise Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs.<span>99</span>/-</div>
         <img src="images/pizza-2.jpg" alt="">
         <div class="name">Cheesy Veggie Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs.<span>89</span>/-</div>
         <img src="images/pizza-3.jpg" alt="">
         <div class="name">Sicilian Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs.<span>105</span>/-</div>
         <img src="images/pizza-4.jpg" alt="">
         <div class="name">Hawaiian Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs<span>115</span>/-</div>
         <img src="images/pizza-5.jpg" alt="">
         <div class="name">Pizza Margherita</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs.<span>130</span>/-</div>
         <img src="images/pizza-6.jpg" alt="">
         <div class="name">Peppy Paneer Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs.<span>145</span>/-</div>
         <img src="images/pizza-7.jpg" alt="">
         <div class="name">Deluxe Extravaganza Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs.<span>150</span>/-</div>
         <img src="images/pizza-8.jpg" alt="">
         <div class="name">Mexican Green Wave Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

      <div class="box">
         <div class="price">Rs.<span>170</span>/-</div>
         <img src="images/pizza-9.jpg" alt="">
         <div class="name">Chicken Pepperoni Pizza</div>
         <form action="" method="post">
            <input type="number" min="1" max="100" value="1" class="qty" name="qty">
            <input type="submit" value="add to cart" name="add_to_cart" class="btn">
         </form>
      </div>

   </div>

</section>

<!-- menu section ends -->

<!-- order section starts  -->

<section class="order" id="order">

   <h1 class="heading">order now</h1>

   <form action="" method="post">

      <div class="display-orders">
         <p>Veggie Paradise Pizza <span>( Rs.69/- x 2 )</span></p>
         <p>Sicilian Pizza <span>( Rs.89/- x 1 )</span></p>
         <p>Peppy Paneer Pizza <span>( Rs.130/- x 2 )</span></p>
         <p>Mexican Green Wave Pizza <span>( Rs.150/- x 1 )</span></p>
      </div>

      <div class="flex">
         <div class="inputBox">
            <span>Your Name :</span>
            <input type="text" name="name" class="box" required placeholder="enter your name" maxlength="30">
         </div>
         <div class="inputBox">
            <span>Your Number :</span>
            <input type="number" name="number" class="box" required placeholder="enter your number" min="0">
         </div>
         <div class="inputBox">
            <span>Payment Mode</span>
            <select name="method" class="box">
               <option value="cash on delivery">Cash on Delivery</option>
               <option value="credit card">Credit Card</option>
               <option value="paytm">paytm</option>
               <option value="paypal">gpay</option>
            </select>
         </div>
         <div class="inputBox">
            <span>Address Line 1 :</span>
            <input type="text" name="flat" class="box" required placeholder="e.g. flat no." maxlength="50">
         </div>
         <div class="inputBox">
            <span>Address Line 2 :</span>
            <input type="text" name="street" class="box" required placeholder="e.g. street name." maxlength="50">
         </div>
         <div class="inputBox">
            <span>Pin Code :</span>
            <input type="number" name="pin_code" class="box" required placeholder="e.g. 123456" min="0">
         </div>
      </div>

      <input type="submit" value="order now" class="btn" name="order">

   </form>

</section>

<!-- order section ends -->

<!-- faq section starts  -->

<section class="faq" id="faq">

   <h1 class="heading">CAQ</h1>

   <div class="accordion-container">

      <div class="accordion active">
         <div class="accordion-heading">
            <span>How does it work?</span>
            <i class="fas fa-angle-down"></i>
         </div>
         <p class="accrodion-content">
            Experience the magic of Our Pizza Taste, where we blend premium ingredients, artisanal craftsmanship, and a passion for flavor to deliver a culinary journey that tantalizes your taste buds with every bite
         </p>
      </div>

      <div class="accordion">
         <div class="accordion-heading">
            <span>How long does it take for delivery?</span>
            <i class="fas fa-angle-down"></i>
         </div>
         <p class="accrodion-content">
           Enjoy hot and delicious pizza delivered to your doorstep within or it's on us – because we understand your craving for a quick and satisfying pizza experience!
         </p>
      </div>

      <div class="accordion">
         <div class="accordion-heading">
            <span>Can I order for huge parties?</span>
            <i class="fas fa-angle-down"></i>
         </div>
         <p class="accrodion-content">
            Planning a big event? Indulge in the flavor-packed joy of Pizza Taste with our special catering services, perfect for large parties and gatherings!
         </p>
      </div>

      <div class="accordion">
         <div class="accordion-heading">
            <span>How much protein it contains?</span>
            <i class="fas fa-angle-down"></i>
         </div>
         <p class="accrodion-content">
             the delicious flavors of Pizza Taste while savoring a protein-packed experience, as our mouth-watering pizzas are crafted to delight your taste buds and provide a satisfying source of protein.
         </p>
      </div>


   </div>

</section>

<!-- faq section ends -->

<!-- footer section starts  -->

<section class="footer">

   <div class="box-container">

      <div class="box">
         <i class="fas fa-phone"></i>
         <h3>phone number</h3>
         <p>6291282812</p>
         <p>8695421369</p>
      </div>

      <div class="box">
         <i class="fas fa-map-marker-alt"></i>
         <h3>our address</h3>
         <p>Block-1, Pavilion Mall, SB Road Model Colony, Shivajinagar,Pune, India - 411016</p>
      </div>

      <div class="box">
         <i class="fas fa-clock"></i>
         <h3>opening hours</h3>
         <p>00:00 am to 10:30 pm</p>
      </div>

      <div class="box">
         <i class="fas fa-envelope"></i>
         <h3>email address</h3>
         <p>pizzataste@gmail.com</p>
         <p>punePizzaTaste@gmail.com</p>
      </div>

   </div>

   <div class="credit">
      &copy; copyright @ 2024 by <span>Mr. Tuhin Pal</span> | all rights reserved!
   </div>

</section>

<!-- footer section ends -->



















<!-- custom js file link  -->
<script src="js/script.js"></script>

</body>
</html>



@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200;300;400;500;600;800&display=swap');

:root{
   --red:#e74c3c;
   --black:#333;
   --white:#fff;
   --light-bg:#f5f5f5;
   --light-color:#666;
   --border:.1rem solid var(--light-color);
   --box-shadow:0 .5rem 1rem rgba(0,0,0,.1);
}

*{
   font-family: 'Nunito', sans-serif;
   margin:0; padding:0;
   box-sizing: border-box;
   outline: none; border:none;
   text-decoration: none;
   transition: .2s linear; 
}

::-webkit-scrollbar{
   width: 1rem;
   height: .5rem;
}

::-webkit-scrollbar-track{
   background-color: transparent;
}

::-webkit-scrollbar-thumb{
   background-color: var(--red);
}

html{
   font-size: 62.5%;
   overflow-x: hidden;
   scroll-behavior: smooth;
   scroll-padding-top: 7.5rem;
}

body{
   background: var(--light-bg);
   overflow-x: hidden;
}

section{
   padding:2rem;
   margin:0 auto;
   max-width: 1200px;
}

.heading{
   text-align: center;
   margin-bottom: 2rem;
   font-size: 4rem;
   color:var(--black);
   text-transform: uppercase;
}

.btn{
   display: block;
   width: 100%;
   margin-top: 1rem;
   border-radius: .5rem;
   padding:1rem 3rem;
   font-size: 2rem;
   color:var(--white);
   background-color: var(--red);
   cursor: pointer;
   text-transform: capitalize;
   text-align: center;
}

.btn:hover{
   background-color:var(--black);
}

.header{
   position: fixed;
   top:0; left:0; right:0;
   background-color: var(--white);
   box-shadow: var(--box-shadow);
   z-index: 1000;
}

.header .flex{
   display: flex;
   align-items: center;
   justify-content: space-between;
   position: relative;
}

.header .flex .logo{
   font-size: 2.5rem;
   color:var(--black);
}

.header .flex .navbar a{
   margin:0 1rem;
   font-size: 2.2rem;
   color:var(--black);
}

.header .flex .navbar a:hover{
   text-decoration: underline;
   color:var(--red);
}

.header .flex .icons div{
   font-size: 2.5rem;
   color:var(--light-color);
   cursor: pointer;
   margin-left: 1.7rem;
}

.header .flex .icons div:hover{
   color:var(--red);
}

.header .flex .icons div span{
   font-size: 2rem;
}

#menu-btn{
   display: none;
}

.user-account{
   position: fixed;
   top:0; right:-110%;
   width: 100%;
   z-index: 1100;
   background-color: var(--white);
   height: 100vh;
   overflow-y: scroll;
}

.user-account.active{
   right: 0;
}

.user-account #close-account{
   text-align: right;
   margin-bottom: 2.5rem;
}

.user-account #close-account span{
   cursor: pointer;
   font-size: 2.5rem;
   color:var(--red);
   text-decoration: underline;
}

.user-account #close-account span:hover{
   color:var(--black);
}

.user-account .user{
   padding:1.5rem;
   text-align: center;
   background-color: var(--light-bg);
   border-radius: .5rem;
}

.user-account .user p{
   font-size: 2rem;
   color:var(--black);
}

.user-account .user p span{
   color:var(--red);
}

.user-account .display-orders{
   padding:3rem 2rem;
   text-align: center;
   background-color: var(--light-bg);
   border-radius: .5rem;
   margin:2rem 0;
   display: flex;
   align-items: flex-start;
   justify-content: center;
   gap:1.5rem;
   flex-wrap: wrap;
}

.user-account .display-orders p{
   padding:1rem 2.5rem;
   font-size: 2rem;
   color:var(--light-color);
   background-color: var(--white);
   border-radius: .5rem;
   box-shadow: var(--box-shadow);
}

.user-account .display-orders p span{
   color: var(--red);
}

.user-account .flex{
   display: flex;
   flex-wrap: wrap;
   gap:2rem;
   align-items: flex-start;
}

.user-account .flex form{
   flex:1 1 40rem;
   border-radius: .5rem;
   padding:2rem;
   background-color: var(--light-bg);
}

.user-account .flex form h3{
   font-size: 2.5rem;
   margin-bottom: 1rem;
   text-transform: uppercase;
   text-align: center;
   color:var(--black);
}

.user-account .flex form .box{
   width: 100%;
   margin:1rem 0;
   border-radius: .5rem;
   background-color: var(--white);
   padding:1.4rem;
   font-size: 1.8rem;
   color:var(--black);
}

.my-orders{
   position: fixed;
   top:0; right:-110%;
   width: 35rem;
   z-index: 1100;
   background-color: var(--light-bg);
   border-left: var(--border);
   height: 100vh;
   overflow-y: scroll;
}

.my-orders.active{
   right: 0;
}

.my-orders #close-orders{
   text-align: right;
   margin-bottom: 2.5rem;
}

.my-orders #close-orders span{
   cursor: pointer;
   font-size: 2.5rem;
   color:var(--red);
   text-decoration: underline;
}

.my-orders #close-orders span:hover{
   color:var(--black);
}

.my-orders .title{
   text-align: center;
   margin-bottom: 1rem;
   color:var(--black);
   font-size: 3rem;
   text-transform: capitalize;
}

.my-orders .box{
   background-color: var(--white);
   border-radius: .5rem;
   padding:1rem 2rem;
   box-shadow: var(--box-shadow);
   margin:1.5rem 0;
}

.my-orders .box p{
   margin:1rem 0;
   font-size: 1.7rem;
   color:var(--light-color);
   line-height: 1.5;
}

.my-orders .box p span{
   color:var(--black);
}

.shopping-cart{
   position: fixed;
   top:0; right:-110%;
   width: 35rem;
   z-index: 1100;
   background-color: var(--light-bg);
   border-left: var(--border);
   height: 100vh;
   overflow-y: scroll;
}

.shopping-cart.active{
   right: 0;
}

.shopping-cart #close-cart{
   text-align: right;
   margin-bottom: 2.5rem;
}

.shopping-cart #close-cart span{
   cursor: pointer;
   font-size: 2.5rem;
   color:var(--red);
   text-decoration: underline;
}

.shopping-cart #close-cart span:hover{
   color:var(--black);
}

.shopping-cart .box{
   display: flex;
   position: relative;
   align-items: center;
   gap:1.5rem;
   border-radius: .5rem;
   box-shadow: var(--box-shadow);
   padding:1.5rem;
   background-color: var(--white);
   margin:1.7rem 0;
}

.shopping-cart .box .fa-times{
   position: absolute;
   top:1.2rem; right:1.2rem;
   font-size: 1.8rem;
   cursor: pointer;
   color:var(--red);
}

.shopping-cart .box .fa-times:hover{
   color:var(--black);
}

.shopping-cart .box img{
   width: 7rem;
}

.shopping-cart .box .content p{
   font-size: 1.8rem;
   color:var(--light-color);
}

.shopping-cart .box .content p span{
   color:var(--red);
}

.shopping-cart .box .content form{
   margin-top: 1.5rem;
   display: flex;
   gap:1rem;
}

.shopping-cart .box .content form .qty{
   border:var(--border);
   border-radius: .5rem;
   padding:1rem;
   font-size: 1.8rem;
   color:var(--black);
   width: 8rem;
}

.shopping-cart .box .content form .fa-edit{
   width: 5.5rem;
   font-size: 1.7rem;
   cursor: pointer;
   border-radius: .5rem;
   background-color: var(--light-bg);
   color:var(--black);
}

.shopping-cart .box .content form .fa-edit:hover{
   background-color: var(--black);
   color:var(--white);
}

@keyframes fadeLeft{
   0%{
      transform: translateX(5rem);
   }
}

@keyframes fadeRight{
   0%{
      transform: translateX(-5rem);
   }
}

.home-bg{
   background:url(../images/home-bg.jpg) no-repeat;
   background-size: cover;
   background-position: center;
}

.home-bg .home .slide-container{
   margin-top: 12rem;
}

.home-bg .home .slide-container .slide{
   display: none;
   align-items: center;
   gap:1.5rem;
   flex-wrap: wrap;
}

.home-bg .home .slide-container .slide.active{
   display: flex;
}

.home-bg .home .slide-container .slide .image{
   flex:1 1 40rem;
   animation: fadeRight .4s linear;
}

.home-bg .home .slide-container .slide .image img{
   width: 100%;
}
.home-bg .home .slide-container .slide .content{
   flex:1 1 40rem;
   text-align: center;
   animation: fadeLeft .4s linear;
}

.home-bg .home .slide-container .slide .content h3{
   color:var(--white);
   margin-bottom: 3rem;
   text-transform: capitalize;
   font-size: 7.5rem;
   text-shadow: var(--box-shadow);
   line-height: 1;
}

.home-bg .home .slide-container .slide .content .fa-angle-left,
.home-bg .home .slide-container .slide .content .fa-angle-right{
   height: 5rem;
   width: 5rem;
   line-height: 4.8rem;
   font-size: 2rem;
   color:var(--black);
   background-color: var(--white);
   margin:0 .5rem;
   box-shadow: var(--box-shadow);
   cursor: pointer;
   border-radius: .5rem;
}

.home-bg .home .slide-container .slide .content .fa-angle-left:hover,
.home-bg .home .slide-container .slide .content .fa-angle-right:hover{
   background-color: var(--red);
   color:var(--white);
}

.about .box-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, 35rem);
   gap:1.5rem;
   align-items: flex-start;
   justify-content: center;
}

.about .box-container .box{
   background-color: var(--white);
   border-radius: .5rem;
   padding:2rem;
   text-align: center;
   box-shadow: var(--box-shadow);
}

.about .box-container .box img{
   width: 100%;
   margin-bottom: 2rem;
}

.about .box-container .box h3{
   font-size: 2.5rem;
   color:var(--black);
}

.about .box-container .box p{
   padding:1rem 0;
   line-height: 2;
   font-size: 1.6rem;
   color:var(--light-color);
}

.menu .box-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, 35rem);
   gap:1.5rem;
   align-items: flex-start;
   justify-content: center;
}

.menu .box-container .box{
   background-color: var(--white);
   border-radius: .5rem;
   padding:2rem;
   text-align: center;
   box-shadow: var(--box-shadow);
   position: relative;
}

.menu .box-container .box img{
   width: 100%;
   margin-bottom: 1rem;
}

.menu .box-container .box .price{
   background-color: var(--black);
   border-radius: .5rem;
   padding:.5rem 1rem;
   font-size: 1.7rem;
   color:var(--white);
   position: absolute;
   top:1rem; left:1rem;
}

.menu .box-container .box .price span{
   font-size: 2.5rem;
}

.menu .box-container .box .name{
   font-size: 2rem;
   color:var(--black);
   margin:.5rem 0;
}

.menu .box-container .box form{
   display: flex;
   gap:1rem;
}

.menu .box-container .box form .qty{
   width: 8rem;
   border:var(--border);
   padding:1rem;
   margin-top: 1rem;
   border-radius: .5rem;
   font-size: 1.8rem;
   color:var(--black);
}

.order form{
   background-color: var(--white);
   box-shadow: var(--box-shadow);
   padding:2rem;
   border-radius: .5rem;
}

.order form .display-orders{
   display: flex;
   align-items: flex-start;
   justify-content: center;
   margin-bottom: 2rem;
   gap:1.5rem;
   flex-wrap: wrap;
   padding:3rem 2rem;
   background-color: var(--light-bg);
   border-radius: .5rem;
}

.order form .display-orders p{
   font-size: 2rem;
   color:var(--light-color);
   background-color: var(--white);
   padding:1rem 3rem;
   border-radius: .5rem;
   box-shadow: var(--box-shadow);
}

.order form .display-orders p span{
   color:var(--red);
}

.order form .flex{
   display: flex;
   flex-wrap: wrap;
   gap:1.5rem;
   justify-content: space-between;
}

.order form .flex .inputBox{
   width: 49%;
}

.order form .flex .inputBox span{
   font-size: 1.8rem;
   color:var(--light-color);
}

.order form .flex .inputBox .box{
   width: 100%;
   background-color: var(--light-bg);
   padding:1.4rem;
   font-size: 1.8rem;
   color:var(--black);
   border-radius: .5rem;
   margin:1rem 0;
}

.faq .accordion-container{
   max-width: 70rem;
   margin:0 auto;
}

.faq .accordion-container .accordion{
   margin:1.5rem 0;
   box-shadow: var(--box-shadow);
}

.faq .accordion-container .accordion .accordion-heading{
   padding:1.5rem;
   background: var(--black);
   color:var(--white);
   cursor: pointer;
   font-size: 2rem;
   display: flex;
   align-items: center;
   justify-content: space-between;
   gap:1.5rem;
}

.faq .accordion-container .accordion .accrodion-content{
   padding:2rem;
   background-color: var(--white);
   line-height: 2;
   color:var(--light-color);
   font-size: 1.6rem;
   display: none;
}

.faq .accordion-container .accordion.active .accrodion-content{
   display: inline-block;
}

.faq .accordion-container .accordion.active .accordion-heading{
   background: var(--red);
}

.faq .accordion-container .accordion.active .accordion-heading i{
   transform: rotate(180deg);
}

.footer .box-container{
   display: grid;
   grid-template-columns: repeat(auto-fit, minmax(27rem, 1fr));
   gap:1.5rem;
   align-items: flex-start;
   justify-content: center;
}

.footer .box-container .box{
   padding:2rem;
   text-align: center;
   background-color: var(--white);
   box-shadow: var(--box-shadow);
   border-radius: .5rem;
}

.footer .box-container .box i{
   height: 6rem;
   width: 6rem;
   line-height: 6rem;
   font-size: 2rem;
   color:var(--white);
   background-color: var(--red);
   border-radius: 50%;
   margin-bottom: .5rem;
}

.footer .box-container .box h3{
   margin:1rem 0;
   color:var(--black);
   text-transform: capitalize;
   font-size: 2rem;
}

.footer .box-container .box p{
   line-height: 2;
   font-size: 1.6rem;
   color:var(--light-color);
}

.footer .credit{
   text-align: center;
   margin-top: 3rem;
   padding:1rem 0;
   padding-top: 3rem;
   border-top: var(--border);
   font-size: 2rem;
   color:var(--black);
   /* padding-bottom: 8rem; */
}

.footer .credit span{
   color: var(--red);
}
















/* media queries  */

@media (max-width:991px){

   html{
      font-size: 55%;
   }
   
}

@media (max-width:768px){

   #menu-btn{
      display: inline-block;
   }

   .header .flex .navbar{
      position: absolute;
      top:99%; left:0; right:0;
      background-color: var(--white);
      border-top: var(--border);
      border-bottom: var(--border);
      clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
   }

   .header .flex .navbar.active{
      clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
   }

   .header .flex .navbar a{
      display: block;
      margin:2rem;
   }

   .home-bg .home .slide-container .slide .content h3{
     font-size: 4rem;
   }

   .order form .flex .inputBox{
      width: 100%;
   }

}

@media (max-width:450px){

   html{
      font-size: 50%;
   }

   .my-orders{
      width: 100%;
      border-left: 0;
   }

   .shopping-cart{
      width: 100%;
      border-left: 0;
   }

   .about .box-container{
      grid-template-columns: 1fr;
   }

   .menu .box-container{
      grid-template-columns: 1fr;
   }
   
}
