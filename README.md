# taehyun.io
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <script src="https://use.fontawesome.com/d1341f9b7a.js"></script>
    <link rel="stylesheet" href="style.css">
    <title>Personal WebSite</title>
  </head>
  <body>
<div class="box">
  <img src="C:\Users\Taehyun Kim\Documents\codes\Sierra 1.jpg" alt="" class="box-img">
  <h1>
Gagan</h1>
<h5>
Student - Gamer</h5>
<p>
  I am a person who likes to pass time by gaming, watching movies, playing, traveling out, and sometimes I just buy some stocks in which I think I will make a lot of profit.</p>
<ul>
<li><a href="#"><i class="fa fa-youtube channel-square" aria-hidden="true"></i></a></li>
<li><a href="#"><i class="fa fa-twitter-square" aria-hidden="true"></i></a></li>
<li><a href="#"><i class="fa fa-apple-square" aria-hidden="true"></i></a></li>
</ul>
</div>
</body>
</html>

body{
    margin: 0;
    padding: 0;
    background: url(https://images.pexels.com/photos/1525041/pexels-photo-1525041.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1) no-repeat;
    background-size: cover;
  }
  .box{
    width: 450px;
    background: rgba(0, 0, 0, 0.4);
    padding: 40px;
    text-align: center;
    margin: auto;
    margin-top: 5%;
    color: white;
    font-family: 'Century Gothic',sans-serif;
  }
  .box-img{
    border-radius: 50%;
    width: 200px;
    height: 200px;
  }
  .box h1{
    font-size: 40px;
    letter-spacing: 4px;
    font-weight: 100;
  }
  .box h5{
    font-size: 20px;
    letter-spacing: 3px;
    font-weight: 100;
  }
  .box p{
    text-align: justify;
  }
  ul{
    margin: 0;
    padding: 0;
  }
  .box li{
    display: inline-block;
    margin: 6px;
    list-style: none;
  }
  .box li a{
    color: rgb(219, 212, 212);
    text-decoration: none;
    font-size: 60px;
    transition: all ease-in-out 250ms;
  }
  .box li a:hover{
    color: #fc0000;
  }
  
