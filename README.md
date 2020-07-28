<!DOCTYPE html>
<html lang="en">
    <head>
        <base href="http://themursea.com">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0">

        <meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://kit.fontawesome.com/a076d05399.js"></script>
<!--Get your own code at fontawesome.com-->

        <title>
                            Online T-shirt Shopping - Themursea
                    </title>

        
        <link href="https://fonts.googleapis.com/css?family=Rubik:300,400,500&display=swap" rel="stylesheet">

                    <link rel="stylesheet" href="http://themursea.com/themes/storefront/public/css/app.css?v=2.0.2">
        
        <link rel="shortcut icon" href="http://themursea.com/storage/media/6ImvUTaPjzQNZav6ggnlkM8wB2ndJ8IlX7pr8GFQ.png" type="image/x-icon">

<style>


.bgimg-1, .bgimg-2, .bgimg-3 {
  position: relative;
  opacity: 0.65;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

}
.bgimg-1 {
  background-image: url("https://wallpapercave.com/wp/FxmXPNK.jpg");
  min-height: 100%;
}

.bgimg-2 {
  background-image: url("https://www.desktopbackground.org/download/o/2015/11/21/1045506_download-free-new-york-city-wallpapers-hd_1920x1200_h.jpg");
  min-height: 400px;
}

.bgimg-3 {
  background-image: url("https://wallpaperaccess.com/full/878.jpg");
  min-height: 400px;
}

.caption {
  position: absolute;
  left: 0;
  top: 50%;
  width: 100%;
  text-align: center;
  color: #000;
}

.caption span.border {
  background-color: #111;
  color: #fff;
  padding: 18px;
  font-size: 25px;
  letter-spacing: 10px;
}

h3 {
  letter-spacing: 5px;
  text-transform: uppercase;
  font: 20px "Lato", sans-serif;
  color: #111;
}

/* Turn off parallax scrolling for tablets and phones */
@media only screen and (max-device-width: 1024px) {
  .bgimg-1, .bgimg-2, .bgimg-3 {
    background-attachment: scroll;
  }
}
</style>
</head>


<body
        class="page-template ltr"
        data-theme-color="#ff749f"
        style="--color-primary: #ff749f;
            --color-primary-hover: #ff4b83;
            --color-primary-transparent: rgba(255, 116, 159, 0.8);
            --color-primary-transparent-lite: rgba(255, 116, 159, 0.3);"
    >
        <div class="wrapper" id="app">
            <section class="top-nav-wrap">
    <div class="container">
        <div class="top-nav">
            <div class="row justify-content-between">
                <div class="top-nav-left d-none d-lg-block">
                    <span>The Mursea  || FREE SHIPPING OVER Rs. 999!</span>
 </div>

                <div class="top-nav-right">
                    <ul class="list-inline top-nav-right-list">
                        <li>
                            <li class="nav-item"><a class="nav-link"><span class="fa fa-home fa-lg"></span> Home</a></li>
                <li class="nav-item active"><a class="nav-link"><span class="fa fa-info fa-lg"></span> About</a></li>
                <li class="nav-item"><a class="nav-link"><span class="fa fa-list fa-lg"></span> Menu</a></li>
                <li class="nav-item"><a class="nav-link"><span class="fa fa-phone fa-lg"></span> Contact</a></li>
                                            </ul>
                </div>
            </div>
        </div>
    </div>

     


</section> <header class="header-wrap">
    <div class="header-wrap-inner">
        <div class="container">
            <div class="row flex-nowrap justify-content-between position-relative">
                <div class="header-column-left">
                    <div class="sidebar-menu-icon-wrap">
                        <div class="sidebar-menu-icon">
                            <span></span>
                            <span></span>
                            <span></span>
                        </div>
                    </div>

                    <a class="header-logo">
                                                    <img src="http://themursea.com/storage/media/6ImvUTaPjzQNZav6ggnlkM8wB2ndJ8IlX7pr8GFQ.png" alt="logo" style="width: 139px; height: 100px;">
                                            </a>
                    
                    
                    
                </div>

               <nav class="navbar navbar-expand-sm">
    <ul class="navbar-nav mega-menu horizontal-megamenu">
                    <li class="nav-item">
    <a  class="nav-link menu-item" target="_self" data-text="HOME">
        
        HOME
    </a>

                </li>
                    <li class="nav-item">
    <a  class="nav-link menu-item" target="_self" data-text="CATELOG">
        
        CATELOG
    </a>

                </li>
                    <li class="nav-item">
    <a  class="nav-link menu-item" target="_self" data-text="ABOUT US">
        
        ABOUT US
    </a>

                </li>
                    <li class="nav-item">
    <a  class="nav-link menu-item" target="_self" data-text="BLOG">
        
        BLOG
    </a>

                </li>
                    <li class="nav-item">
    <a class="nav-link menu-item" target="_self" data-text="CONTACT US">
        
        CONTACT US
    </a>

                </li>
            </ul>
</nav>

                

                <div class="header-column-right d-flex">
                    
                    
                    <a href="http://themursea.com/account/wishlist" class="header-wishlist">
                        <div class="icon-wrap">
                            <i class="fas fa-heart" style="font-size:30px;color:red;text-shadow:2px 2px 4px #000000;"></i>
                            <div class="count" v-text="wishlistCount"></div>
                        </div>

                        <span>Favorites</span>
                    </a>
                    
                    

                    <div class="header-cart">
                        <div class="icon-wrap">
                            <i class="fas fa-cart" style="font-size:30px;color:red;text-shadow:2px 2px 4px #000000;"></i>
                            <div class="count" v-text="cart.quantity"></div>
                        </div>

                        <span v-html="cart.subTotal.inCurrentCurrency.formatted"></span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</header>
            <section class="navigation-wrap">
    <div class="container">
        <div class="navigation-inner">
            
            <span class="navigation-text">
                
            </span>
        </div>
    </div>
</section>

<div style="color: #777;background-color:white;text-align:center;padding:50px 80px;text-align: justify;">
  <h3 style="text-align:center;">Parallax Demo</h3>
  <p>Parallax scrolling is a web site trend where the background content is moved at a different speed than the foreground content while scrolling. Nascetur per nec posuere turpis, lectus nec libero turpis nunc at, sed posuere mollis ullamcorper libero ante lectus, blandit pellentesque a, magna turpis est sapien duis blandit dignissim. Viverra interdum mi magna mi, morbi sociis. Condimentum dui ipsum consequat morbi, curabitur aliquam pede, nullam vitae eu placerat eget et vehicula. Varius quisque non molestie dolor, nunc nisl dapibus vestibulum at, sodales tincidunt mauris ullamcorper, dapibus pulvinar, in in neque risus odio. Accumsan fringilla vulputate at quibusdam sociis eleifend, aenean maecenas vulputate, non id vehicula lorem mattis, ratione interdum sociis ornare. Suscipit proin magna cras vel, non sit platea sit, maecenas ante augue etiam maecenas, porta porttitor placerat leo.</p>
</div>

<div class="bgimg-2">
  <div class="caption">
  <span class="border" style="background-color:transparent;font-size:25px;color: #f7f7f7;">LESS HEIGHT</span>
  </div>
</div>

<div style="position:relative;">
  <div style="color:#ddd;background-color:#282E34;text-align:center;padding:50px 80px;text-align: justify;">
  <p>Scroll up and down to really get the feeling of how Parallax Scrolling works.</p>
  </div>
</div>

<div class="bgimg-3">
  <div class="caption">
  <span class="border" style="background-color:transparent;font-size:25px;color: #f7f7f7;">SCROLL UP</span>
  </div>
</div>

<div style="position:relative;">
  <div style="color:#ddd;background-color:#282E34;text-align:center;padding:50px 80px;text-align: justify;">
  <p>Scroll up and down to really get the feeling of how Parallax Scrolling works.</p>
  </div>
</div>

<div class="bgimg-1">
  <div class="caption">
  <span class="border">COOL!</span>
  </div>
</div>
