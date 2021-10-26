
=======================================================

Article Title: Disney plus clone
Author Name: Shivam Jha
Author Profile: github.com/shivamm-jha
Date: 26th october 2021

=======================================================

# Dinsey plus landing page
--------------------------


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Disney</title>
    <link rel="stylesheet" href="style.css" />
    <link
  rel="stylesheet"
  href="https://unpkg.com/swiper@7/swiper-bundle.min.css"
/>

    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous">
  </head>
  <body>

      <!-- navigation bar -->

      
    <nav class="navbar">
      <img src="images/logo.png" alt="" class="brand-logo" />
      <input type="checkbox" name="" id="click">
      <label for="click" class="menu-btn">
        <i class="fas fa-bars"></i>
      </label>
      <ul class="nav-links">
        <li class="nav-items"><a href="#">Tv</a></li>
        <li class="nav-items"><a href="#">Movies</a></li>
        <li class="nav-items"><a href="#">Sports</a></li>
        <li class="nav-items"><a href="#">Premium</a></li>
      </ul>

    

      <div class="right-container">
        <input type="text" class="search-box" placeholder="Search" />
        <button class="sub-btn">subscribe</button>
        <a href="#" class="login-link">login</a>
      </div>
    </nav>



    <!-- carousel container -->






    <!-- Slider main container -->
<div class="swiper">
    <!-- Additional required wrapper -->
    <div class="swiper-wrapper">
      <!-- Slides -->
      <div class="swiper-slide">
          <img src="images/slider 1.PNG" alt="">
      </div>
      <div class="swiper-slide">
          <img src="images/slider 2.PNG" alt="">
      </div>
      <div class="swiper-slide">
          <img src="images/slider 3.PNG" alt="">
      </div>
      <div class="swiper-slide">
        <img src="images/slider 4.PNG" alt="">
    </div>
    <div class="swiper-slide">
        <img src="images/slider 5.PNG" alt="">
    </div>
      
      ...
    </div>
    <!-- If we need pagination -->
    <div class="swiper-pagination"></div>
  
    <!-- If we need navigation buttons -->
    <div class="swiper-button-prev"></div>
    <div class="swiper-button-next"></div>
  
   
  </div>





    <div class="video-card-container">
      <div class="video-card">
        <img src="images/disney.PNG" alt="" class="video-card-image" />
        <video src="videos/disney.mp4" mute loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/pixar.PNG" alt="" class="video-card-image" />
        <video src="videos/pixar.mp4" mute loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/marvel.PNG" alt="" class="video-card-image" />
        <video src="videos/marvel.mp4" mute loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/star-wars.PNG" alt="" class="video-card-image" />
        <video src="videos/star-war.mp4" mute loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/geographic.PNG" alt="" class="video-card-image" />
        <video src="videos/geographic.mp4" mute loop class="card-video"></video>
      </div>
    </div>

    <h1 class="title">recommended for you</h1>
    <div class="movies-list">
      <div class="card-container">
        <div class="card">
          <img src="images/poster 1.png" alt="" class="card-image" />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watch list</button>
          </div>
        </div>
        <div class="card">
            <img src="images/poster 2.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 3.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 4.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 5.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 6.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 7.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 8.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 1.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 2.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 3.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 4.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 5.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
      </div>





      <h1 class="title">trending</h1>
      <div class="card-container">
        <div class="card">
          <img src="images/poster 5.png" alt="" class="card-image" />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watch list</button>
          </div>
        </div>
        <div class="card">
            <img src="images/poster 6.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
        </div>
        <div class="card">
            <img src="images/poster 7.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
        </div>
        <div class="card">
            <img src="images/poster 8.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
        </div>
        <div class="card">
            <img src="images/poster 9.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
         </div>
         <div class="card">
            <img src="images/poster 10.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 11.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 12.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 2.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 1.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 3.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
        
        
      </div>





      <h1 class="title">popular shows</h1>
      <div class="card-container">
        <div class="card">
          <img src="images/poster 7.png" alt="" class="card-image" />
          <div class="card-body">
            <h2 class="name">movie name</h2>
            <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
            <button class="watchlist-btn">add to watch list</button>
          </div>
        </div>
        <div class="card">
            <img src="images/poster 8.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 9.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 10.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 11.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 12.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 4.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 1.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 3.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 2.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 6.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 9.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
          <div class="card">
            <img src="images/poster 4.png" alt="" class="card-image" />
            <div class="card-body">
              <h2 class="name">movie name</h2>
              <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
              <button class="watchlist-btn">add to watch list</button>
            </div>
          </div>
      </div>
    </div>




    <!-- footer of the page -->
    <footer>
        <div class="left-container">
            <div class="left-footer-links">
                <ul>
                    <li><a href="#">About Disney+hotstar</a></li>
                    <li><a href="#">terms of use</a></li>
                    <li><a href="#">privacy policy</a></li>
                    <li><a href="#">FAQ</a></li>
                    <li><a href="3">feedback</a></li>
                    <li><a href="3">careers</a></li>
                </ul>
            </div>



            <div class="left-footer-text">
                <p>© 2021 STAR. All Rights Reserved. HBO, Home Box Office and all related channel and programming logos are service marks of, and all related programming visuals and elements are the property of, Home Box Office, Inc. All rights reserved.</p>
            </div>



        </div>

        <div class="footer-right-container">
            <div class="right-social-icons">
                <div class="connect-text">
                    <p>connect with us</p>
                </div>
                <div class="social-icons">
                    <span class="social"><i class="fab fa-facebook-f"></i></span>
                    <span class="social"><i class="fab fa-twitter"></i></span>
                </div>
            </div>


            <div class="right-play-store-app-store">
                <div class="icon-card">
                    <div class="play-icon">
                        <span><i class="fab fa-apple"></i></span>
                    
                    </div>
                    <div class="text-icon">
                        <p>Get it on</p>
                        <h1>app store</h1>
                    </div>
                </div>

                <div class="icon-card">
                    <div class="play-icon">
                        <span><i class="fab fa-google-play"></i></span>
                    
                    </div>
                    <div class="text-icon">
                        <p>Get it on</p>
                        <h1>google play</h1>
                    </div>
                </div>
            </div>
        </div>
    </footer>
  </body>
  <script src="https://unpkg.com/swiper@7/swiper-bundle.min.js"></script>
  <script src="app.js"></script>
</html>








@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');

*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
}
body{
    width: 100%;
    background-color: #0c111b;
    position: relative;
    font-family: 'Roboto', sans-serif;

}
.navbar{
    width: 100%;
    height: 80px;
    position: fixed;
    top: 0;
    left: 0;
    padding: 0 4%;
    background: #0c111b;
    z-index: 9;
    display: flex;
    align-items: center;
}
.brand-logo{
    height: 70px;
}
.nav-links{
    margin-top: 10px;
    display: flex;
    list-style: none;

}
.nav-links a{
    text-decoration: none;
    margin-left: 20px;
    text-transform: capitalize;
    color: #fff;
    opacity: 0.9;
}
.menu-btn
{
    color: #fff;
    font-size: 22px;
    cursor: pointer;
    display: none;
}
#click{
    display: none;
}
.right-container{
    display: block;
    margin-left: auto;
}
.search-box{
    border: none;
    border-bottom: 1px solid #aaa;
    background: transparent;
    outline: none;
    height: 30px;
    color: #fff;
    width: 250px;
    text-transform: capitalize;
    font-size: 16px;
    font-weight: 500;
    transition: .5s;
}

.search-box:focus{
    width: 400px;
    border-color: #1f80e0;
}

.sub-btn{
    background: #1f80e0;
    height:30px;
    padding: 0 20px;
    color: #fff;
    border-radius: 5px;
    border: none;
    outline: none;
    text-transform: uppercase;
    font-weight: 700;
    font-size: 12px;
    margin: 0 10px;


}

.login-link{
    color:#fff;
    opacity: 0.9;
    text-transform: uppercase;
    font-size: 15px;
    font-weight:700 ;
    text-decoration: none;

}

/*  carosuel youtube vide0 */

.swiper {
    width: 80%;
    padding: 20px 0;
    height: 35vw;
    margin-top: 80px;
    margin-bottom: 3rem;
    display: flex;
    align-items: center;
    justify-content: center;
    
  }
  

  .swiper-slide img{
    width: 100%;
    min-height: 100%;
    object-fit: cover;
    display: block;
  }



  /* ------------------- */



.video-card-container{
    position: relative;
    width: 92%;
    margin: auto;
    height: 10vw;
    display: flex;
    margin-bottom: 20px;
    justify-content: space-between;
}

.video-card{
    position: relative;
    min-width: calc(100%/5 - 10px);
    width: calc(100%/5 - 10px);
    height: 100%;
    border-radius: 5px;
    overflow: hidden;
    background: #030b17;
}
.card-video,
.video-card-image{
    width: 100%;
    height: 100%;
    object-fit: contain;
}

.card-video{
    position: absolute;
}
.video-card:hover .video-card-image{
    display: none;
}

.title{
    color:#fff;
    opacity: 0.9;
    padding-left: 4%;
    text-transform: capitalize;
    font-size: 22px;
    font-weight: 500;

}

.movies-list{
    width: 100%;
    height: 220px;
    position: relative;
    margin: 10px 0 20px;
}

.card-container{
    position: relative;
    width: 92%;
    padding-left: 10px ;
    height:220px;
    display: flex;
    margin: 0 auto;
    align-items: center;
    overflow-x: auto;
    overflow-y:visible ;
    scroll-behavior: smooth;

}

.card-container::-webkit-scrollbar{
    display: none;
}

.card{
    position: relative;
    min-width: 150px;
    width: 150px;
    height: 200px;
    border-radius: 5px;
    overflow: hidden;
    margin-right: 10px;
    transition: .5s;
    background: #000;
}
.card-image{
    width:100%;
    height: 100%;
    object-fit: cover;
}
.card:hover{
    transform: scale(1.1);
}
.card:hover .card-body{
    opacity: 1;
}
.card-body{
    opacity: 0;
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left:0;
    z-index: 2;
    background: linear-gradient(to bottom, rgba(4, 8, 15, 0), #192133 98%);
    padding: 10px;
    transition: 0.5s;
}

.name{
    color: #fff;
    font-size: 15px;
    font-weight: 500;
    text-transform: capitalize;
    margin-top: 60%;
}
.des{
    color: #fff;
    opacity: 0.8;
    margin: 5px 0;
    font-weight:500;
    font-size: 12px;
}

.watchlist-btn{
    position: relative;
    width:100%;
    text-transform: capitalize;
    background: none;
    border: none;
    font-weight: 500;
    text-align:right;
    color: rgba(255, 255, 255, 0.8);
    margin: 5px 0;
    cursor: pointer;
    padding: 10px 5px;
    border-radius: 5px;


}

.watchlist-btn::before{
    content: "";
    position: absolute;
    top:0;
    left: -5px;
    width: 35px;
    height: 35px;
    background-image: url(images/add.png);
    background-size: cover;
    transform: scale(0.4);
}

.watchlist-btn:hover{
    color:#fff;
    background: rgba(255, 255, 255, 0.1);
}



/* left footer  */

footer{
    margin-top: calc(100vh - 10rem);
    width: 90vw;
    margin-left: auto;
    margin-right: auto;
    display: flex;
    /* justify-content: center;
    align-items: center; */
    margin-bottom: 2rem;
    border-top:1px solid white ;
    padding-top: 3rem;
    
}

.left-footer-links ul li{
    list-style: none;
}
.left-footer-links ul li a{
    color:#fff;
    text-decoration: none;
    opacity: 0.8;
    text-transform: capitalize;
    font-size: .95rem;
}
.left-footer-links ul{
    display: flex;

}
.left-footer-links ul li{
    margin-right: 1rem;
}
.left-footer-text{
    margin-top: 2rem;
    color: #fff;
    display: flex;
    flex-wrap: wrap;
    font-size: .85rem;
}

.left-container{
    width: 50rem;
    position: relative;
    left: 0;
  
}

.footer-right-container{
    display: flex;
    justify-content: space-evenly;
    align-items: flex-start;

}
.right-social-icons{
    display: flex;
    /* justify-content: center;
    align-items: center; */
    flex-direction: column;
}
.connect-text{
    color: #fff;
    opacity: 0.8;
    margin-bottom: 1rem;
    text-transform: capitalize;
}
.social{
    color: #fff;
    opacity: 0.8;
    font-size: .85rem;
    background-color: rgb(51, 50, 50);
    padding: .5rem;
    margin-right: .8rem;
    border-radius: 5px;
}

.right-play-store-app-store{
    margin-left: 10rem;
    display: flex;
    
}

.icon-card{
    display: flex;
    justify-content: space-around;
    align-items: center;
    color: #fff;
    margin-left:.5rem ;
    padding: .4rem;
    background-color:rgb(51, 50, 50) ;
}
.play-icon span i{
    font-size: 1.4rem;
}
.icon-card p{
    font-size: .7rem;
}
.icon-card h1{
    font-size: .9rem;
    text-transform: capitalize;
}


/* responsive design */
@media (max-width:820px) {
    .left-footer-links ul li a{
        font-size: .6rem;
    }
    .left-footer-text{
        font-size: .6rem;
    }
    .connect-text{
        font-size: .7rem;
    }
    .social-icons span i{
        font-size: .7rem;
        padding: .1rem;
    }
    .social-icons{
        display: flex;
    }
    .text-icon p{
        font-size: .6rem;
    }
    .text-icon h1{
        font-size: .7rem;
    }
    .right-play-store-app-store{
        display: flex;
        flex-direction: column;
        margin-left: 0;
    }
    .icon-card{
        margin-bottom: .2rem;
    }
    .footer-right-container{
        display: flex;
        flex-direction: column;
    }
    .video-card{
        width: 50rem;
    }
}


/* for responsive side nav bar */
@media (max-width:900px){
    .navbar ul{
        position: fixed;
        top: 70px;
        left: -100%;
        background: #0c111b;
        height: 100%;
        width: 100%;
        display: block;
        text-align: center;
        justify-content: center;
        transition: all 0.3s ease-in;
    }
    .navbar ul li{
        margin:80px 0;
    }
    .navbar ul li a{
        font-size: 20px;
        
    }
    .navbar ul li a:hover{
        color: cyan;
        background: none;
    }
    /* right container */
    .right-container{
        position: fixed;
        bottom: 7%;
        left: 50%;
        transform: translate(-50%,-50%);
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .right-container{
        display: none;
    }
    
    .menu-btn{
        display: block;
        position: fixed;
        top: 2rem;
        right: 2rem;
    }
    /* when check box is checked */
    #click:checked ~ ul{
        left: 0;
    }
    #click:checked ~ .menu-btn i:before{
        content: "\f00d";
    }


     
    /*------------------- for footer------------ */
    
}
@media (max-width:1220px){
    footer{
        margin-top: 34rem;
        max-width: 90vw;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
    }
    .left-container{
        width: 90vw;
    }
    .left-footer-text{
        max-width: 90vw;
    }
    .footer-right-container{
        width:90vw;
        text-align: center;
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        flex-direction: row;
        margin-top: 2rem;
        
    }
}












const swiper = new Swiper('.swiper', {
    // Optional parameters
   
  
    // If we need pagination
    pagination: {
      el: '.swiper-pagination',
    },
  
    // Navigation arrows
    navigation: {
      nextEl: '.swiper-button-next',
      prevEl: '.swiper-button-prev',
    },
  
    // And if we need scrollbar
    scrollbar: {
      el: '.swiper-scrollbar',
    },
  });

//  video cards

const videoCards = [...document.querySelectorAll('.video-card')];
videoCards.forEach(item=> {
    item.addEventListener('mouseover', ()=>{
        let video = item.children[1];
        video.play();
    });

    item.addEventListener('mouseleave', ()=>{
        let video = item.children[1];
        video.pause();
    });
})




