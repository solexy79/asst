<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="css/style.min.css">
  <script src="https://kit.fontawesome.com/14b555e212.js" crossorigin="anonymous"></script>
  <link href="https://fonts.googleapis.com/css2?family=Raleway" rel="stylesheet">
  <title>Welcome to Olawale networks  </title>
</head>
<body>
  <nav class="navbar bg-dark">
    <h1>
      <a href="dashboard.html">
        <i class="fas fa-code"></i> Olawale Networks
      </a>
    </h1>
    <ul>
      <li><a href="profiles.html">Contact Us</a></li>
      <li><a href="#sign-up">Register </a></li>
      <li><a href="login.html">LogIn</a></li>
    </ul>
  </nav>
  <header class="landing">
    <div class="dark-overlay">
      <div class="landing-inner">
        <h1 class="x-large">Olawale Networks</h1>
        <p class="lead">Buy airtime, data, and pay bills easily at a reduced rate</p>
        <div class="buttons">
          <a href="#sign-up" class="btn btn-primary">Sign Up</a>
          <a href="login.html" class="btn btn">Login</a>
        </div>
      </div>
    </div>
  </header>
  <section class="container">
      <a name="sign-up"></a>
      <h1 class="large text-primary"> Sign Up</h1>
      <p class="lead"><i class="fas fa-user"></i>Create Your Account</p>
      <form action="" class="form" id="form">
        <div class="form-group">
          <label>Name</label>
          <input type="text" id="username">
          <small>Error message</small>          
        </div>
        <div class="form-group">
          <label>Email Address</label>
          <input type="email" id="email">
          <small>Error message</small>   
        </div>
        <div class="form-group">
          <label>Password</label>
          <input type="password" minlength="6" id="password">
          <small>Error message</small>
        </div>
        <div class="form-group">
          <label>Confirm Password</label>  
          <input type="password" minlength="6" id="password2">
          <small>Error message</small>   
        </div>
        <input type="submit" value="Register" class="btn btn-primary my-1">
      </form>
      <p class="my-1">
        Already have an account? <a href="login.html">Sign In</a>
      </p>
  </section>
  <script src="main.js"></script> 
</body>
</html>
