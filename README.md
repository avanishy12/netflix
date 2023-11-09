# netflif web pade design 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width= , initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        header {
            padding: 10px 30px;
            position: relative;
            z-index: 10;
        }
        .logo{
            background-image: url("netflilogo-removebg-preview.png");
            height: 73px;
            width: 200px;
            background-size:cover ;
            background-position: center;
            background-repeat: no-repeat;
            display: inline-block;
            /*border: 2px solid red;*/
        }
        .language {
            background-color: transparent;
            color: white;
            padding: 6px 10px;
            border-radius: 3px;
            position: absolute;
            top: 35px;
            right: 148px;
            font-size: 17px;
        }
        nav{
            display: inline-block ;
            position: absolute;
            top: 32px;
            right: 50px;
        }
        
        nav button{
            background-color: red;
            color: white;
            font-size: 18px;
            padding: 8px 10px;
            border: none;
            border-radius: 3px;
        }
        .hero-image{
            background-image: linear-gradient( 
                rgba(0, 0, 0, 0.503),
                rgba(0, 0, 0, 0.720)),
                url("backgroundimg.jpeg");
                /*border: 3px solid black;*/
                height: 850px;
                background-repeat: no-repeat;
                background-size:cover;
                position: relative;
                top: -100px;
        }
        .hero-content {
            text-align: center;
            position: absolute;
            /*border: 4px solid white;*/
            top: 230px;
            left: 379px;
         }
         .hero-content h1 {
            color: white;
            font-size: 60px;
            font-weight: bold;
         }
        .hero-content h2{
            color: white;
            font-size: 25px;
            padding: 10px 0px;
        }
        .hero-content p {
            color: white;
            padding: 10px 0px;
            font-size: 20px;
        }
        .hero-content form :nth-child(1){
            height: 60px;
            width: 450px;
            padding: 0px 10px ;
            font-size: 18px;
        }
        .hero-content form :last-child{
            height: 40px;
            background-color: red;
            padding: 0px 20px;
            /*font-sizi: 20px;*/
            color: white;
            height: 60px;
            border: none;
            width: 171px;
            font-size: 18px;
        }
        .hero-content form :last-child:hover{
          
          background-color:rgba(255, 0, 0, 0.82);
        }
    
         
        .TV-block {
    background-image: url("tvvideo.m4v");
  /* border: 2px solid red; */
  background-color: black;
  color: white;
  position: relative;
  top: -100px;
  border-top: 10px solid #222;
  padding: 50px 100px;
  height: 428px;
  overflow: hidden;
}

.TV-content {
  /* border: 2px solid red; */
  display: inline-block;
  position: absolute;

  top: 133px;
  left: 150px;
}

.TV-content h2 {
  font-size: 60px;
  padding: 10px 0px;
}

.TV-content h3 {
  font-size: 25px;
}
.TV-video {
  border: 2px solid red;
  display: inline-block;
  position: absolute;
  right: 100px;
  top: 100px;
}

.TV-video img {
  position: absolute;
    width: 617px;
    left: -540px;
    bottom: -328px;
    z-index: 2;
}
.TV-video video {
  position: absolute;
  width: 290px;
  left: -379px;
  bottom: -194px;
  z-index: 1;
}




        /*.story1{
            background-color: black;
            background-size: cover;
            position: relative;
            border-bottom: 0px solid #171616;
            top: -100;
            height: 470px;
            color: white;
            box-sizing: border-box;
            padding: 130px 100px;
        }
        .story1 h1{
        font-size: 50px;
        }
        .story1 h2{
            font-size: 25px;
            padding: 24px 0px;
        }
        .hero-story1{
            background-image: url("mobile-0819.jpg");
            background-repeat: no-repeat;
            background-size: 250px;
            height: 400px;
            width: 590px;
            padding: 100px 120px;
            display: inline-block;
        }
        .story3{
            background-color: black;
            background-size: cover;
            position: relative;
            border-bottom: 0px solid #171616;
            top: -100px;
            height: 500px;
            color: white;
            box-sizing: border-box;
            padding: 190px 100px;
        }
        .story3 h1{
            font-size: 50px;
        }
        .story3 h2{
            font-size: 25px;
            padding: 22px 0px;
        }
        .hero-story{
            background-image: url("tv.png");
            background-repeat: no-repeat;
            background-size: 510px;
            height: 440px;
            width: 500px;
            padding: 0px 120px 1px 100px;
            display: inline-block;
        }
        .video{
            background-color: transparent;
        }
        .story4{
            background-color: black;
            background-size: cover;
            position: fixed;
        }*/


        </style>
</head>
<body>
    <header>
   <div class="logo"></div>
    <select name="language" class="language">
    <option value="english">English</option>
    <option value="hindi">हिन्दी</option>
    </select>
    <nav>
        <button class="sign">Sign In</button>
    </nav>
  </header> 
  <section class="hero-image">
    <section class="hero-content">
        <h1>
            unlimited movies, TV <br/>
            shows and more.
         </h1>
         <h2>watch anywhere. Cancel anytime.</h2>
         <p>
            ready to watch? Enter your email to create or restart your membership.
         </p>
         <form action ="">
            <input
            type="serarch"
            name=""
            id=""
            placeholder="Email address" />
            <input type="submit" value="Started>"/>
        </form>
    </section>
  </section>
  <section class="TV-block">
    <article>
      <div class="TV-content">
        <h2>Enjoy on your TV.</h2>
         <h3> 
          Watch on smart TVs, PlayStation, Xbox,<br />
          Chromecast, Apple TV, Blu-ray players and<br />
          more.
        </h3>
      </div>
      <div class="TV-video">
        <img
          src="tv.png"
          alt="tvvideo"
          />
          <video autoplay loop>
            <source=""
              src=""
            />
          </video>
        </div>
      </article>
    </section>
    

  <section class="TV-block">
    <article>
      <div class="TV-content">
        <h2>Download your shows to watch offline.</h2>
        <h3>
            Save your favourites easily and always have something to watch.<br/>
        </h3>
      </div>
      <div class="TV-video">
        <img
          src="mobilenet.jpg"
          alt=""
        />
        <video autoplay loop>
          <source
            src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-in-0819.m4v"
          />
        </video>
      </div>
    </article>
  </section>


  <section class="TV-block">
    <article>
      <div class="TV-content">
        <h2>Watch everywhere..</h2>
        <h3>
            Stream unlimited movies and TV shows on your phone,<br/>
             tablet, laptop, and TV.<br/>
        </h3>
      </div>
      <div class="TV-video">
        <img
          src="device.png"
          alt=""
        />
        <video autoplay loop>
          <source
            src="videonetflix.mp4"
          />     .
        </video>
      </div>
    </article>
  </section>
</body>



<section class="TV-block">
    <article>
      <div class="TV-content">
        
        <h2>Create profiles for children.</h2>
        <h3>
             Send children on adventures with their </br>
             favourite characters in a space made just for </br>
             them—free with your membership.</br>
        </h3>
      </div>
      <div class="TV-video">
        <img
          src="netflixchild.png"
          alt=""
          
        />
         <video autoplay loop> 
          <source
            src=""
          /> 
        </video>
      </div>
    </article>
  </section>

 </body>
</html> 
