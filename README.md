<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Awesome Landing Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header{
      width:100%;
      height: 100vh;
      background-image:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)),url("image.jpg");
      background-repeat: no-repeat;
      background-size: cover;
    } 
    nav{
      width: 100%;
      height:100px;
      color: white;
      display: flex;
    }
    .logo{
      font-size: 1.5em;
      letter-spacing: -1px;
    }
    .container a {
      text-decoration: none;
      color: #fff;
      padding: 10px 80px;
      font-size: 20px;
    }
    ul {
      float:right;
      line-height: 80px;
    }
    ul li {
      display: inline-block;
      list-style: none;
      padding: 10px 5px;
    }
    ul li a{
      color: #fff;
      text-decoration: none;
      text-transform: uppercase;
      border-radius: 5px;
      padding:7px 8px;
    }
    ul li a:hover{
      background-color: #eb7620;
      transition: 0.5s ease;
    }
    ul li active{
      background-color: #eb7620;
    }
    .content{
      max-width: 650px;
      position: absolute;
      top:50%;
      left: 50%;
      transform:translate(-50%,-50%);
      text-align:center;
      color:#fff;
    }
    .content span{
      letter-spacing: 2px;
    }  
    .content h1{
      font-size: 3.5em;
    }  
    .content .btn{
      color: #fff;
      padding: 12px 25px;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      text-decoration: none;
      background-color: #f15048;
    }
    .content .btn:hover{
      background-color: #4399fa;
      transition: 0.5s ease;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
 <header>
  <nav>
    <div class="logo">
      Let's design...
    </div>
    <div class="container">
    <ul>
      <li><a href=""class="active">Home</a></li>
      <li><a href="">About</a></li>
      <li><a href="">Ideas</a></li>
      <li><a href="">Contact</a></li>
  </ul>
    <section class="content">
      <span><h1>Welcome to Projects</span></h1>
      <h1>Websites Ideas</h1>
      <p>Hey!! It's is best chances to design your best projects..</p>
      <p>Here we are providing you ideas for your projects.</p>
      <a href=""class="btn">Download Now</a>  </section>
    </div>
  </header>
  
  <footer>
    <p>&copy; 2023 My Awesome Landing Page. All rights reserved.</p>
  </footer>
</body>
</html>
