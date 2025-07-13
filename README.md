<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Home</title>
  <link rel="stylesheet" href="style.css" />
  <link href="<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Redeemer's Private Secondary School</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="logo">Redeemer's Private Secondary School</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="C:\Users\marve\OneDrive\Desktop\WEBSITES\main\about.html">About</a></li>
        <li><a href="C:\Users\marve\OneDrive\Desktop\WEBSITES\main\gallery.html">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
   <a> <img src="C:\Users\marve\OneDrive\Documents\RPSS LOGO.png"style="width:100;" height="200" text-align="center;"
     alt="RPSS LOGO" </a>

    <h1>Welcome to Redeemer's Private Secondary School</h1>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>
      Redeemer's Private Secondary School is committed to academic excellence,
      spiritual growth, and character development. We prepare students for a
      bright future in a nurturing environment.
    </p>
  </section>

  <section id="mission" class="section">
    <h2>Our Mission & Vision</h2>
    <ul>
      <li>✔ Provide quality education with Christian values</li>
      <li>✔ Inspire a passion for learning and leadership</li>
      <li>✔ Empower students for global impact</li>
    </ul>
  </section>
  <section>

<style>
.gallery {position: center; width: 70vw;
margin: 5px auto; overflow: hidden;}
.gallery img {width: 70%; height: 30%;
object-fit: cover; display: none;}
.gallery img.active {display: block;}
.dots {text-align: center; margin-top: 0px;}
.dot {height: 10px; width: 10px; background-color: #bbb; border-radius:
50%; display: inline-block; margin: 0 0px; cursor: pointer;}
.dot.active {background-color: #333;}
</style>
<div class="gallery">
<img src="C:\Users\marve\OneDrive\Documents\rpss classroom.jpg" class="active">
<img src="C:\Users\marve\OneDrive\Documents\rpss culinary.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss lab.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss ict.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss music.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss table tennis.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss games.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss fitness.jpg">
</div>
<div class="dots">
<span class="dot active"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
</div>
<script>
let images = document.querySelectorAll('.gallery img');
let dots = document.querySelectorAll('.dot');
let currentIndex = 0;
// Auto slide images
setInterval(() => { currentIndex = (currentIndex + 1) %
images.length; updateGallery(); }, 3000);
// Update gallery
function updateGallery() { images.forEach((image, index) =>
{ image.classList.remove('active'); dots[index].classList.remove('active');
if (index === currentIndex) { image.classList.add('active');
dots[index].classList.add('active'); } }); }
// Click event for dots
dots.forEach((dot, index) => { dot.addEventListener('click', () =>
{ currentIndex = index; updateGallery(); }); });
</script>

</section>
  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: info@redeemersschool.edu.ng</p>
    <p>Phone: +234-123-456-7890</p>
    <p>Address: 10 Grace Avenue, Lagos, Nigeria</p>
  </section>

  <footer>
    <p>&copy; 2025 Redeemer's Private Secondary School. All rights reserved.</p>

  
</body>
</html>





<style>
.gallery {position: center; width: 100vw;
margin: 5px auto; overflow: hidden;}
.gallery img {width: 100vw; height: 650px;
object-fit: cover; display: none;}
.gallery img.active {display: block;}
.dots {text-align: center; margin-top: 0px;}
.dot {height: 10px; width: 10px; background-color: #bbb; border-radius:
50%; display: inline-block; margin: 0 0px; cursor: pointer;}
.dot.active {background-color: #333;}
</style>
<div class="gallery">
<img src="C:\Users\marve\OneDrive\Documents\rpss classroom.jpg" class="active">
<img src="C:\Users\marve\OneDrive\Documents\rpss culinary.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss lab.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss ict.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss music.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss table tennis.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss games.jpg">
<img src="C:\Users\marve\OneDrive\Documents\rpss fitness.jpg">
</div>
<div class="dots">
<span class="dot active"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
<span class="dot"></span>
</div>
<script>
let images = document.querySelectorAll('.gallery img');
let dots = document.querySelectorAll('.dot');
let currentIndex = 0;
// Auto slide images
setInterval(() => { currentIndex = (currentIndex + 1) %
images.length; updateGallery(); }, 3000);
// Update gallery
function updateGallery() { images.forEach((image, index) =>
{ image.classList.remove('active'); dots[index].classList.remove('active');
if (index === currentIndex) { image.classList.add('active');
dots[index].classList.add('active'); } }); }
// Click event for dots
dots.forEach((dot, index) => { dot.addEventListener('click', () =>
{ currentIndex = index; updateGallery(); }); });
</script>



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Register</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet"/>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      height: 100vh;
      background: linear-gradient(to bottom left, #008000, #ffffff, #6a0dad);
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .register-container {
      background: white;
      padding: 2.5rem;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
      width: 370px;
      animation: slideIn 1s ease-in-out;
    }

    .register-container h2 {
      text-align: center;
      margin-bottom: 1.5rem;
      color: #008000;
    }

    .input-group {
      margin-bottom: 1.2rem;
      position: relative;
    }

    .input-group label {
      display: block;
      margin-bottom: 0.4rem;
      color: #6a0dad;
    }

    .input-group input {
      width: 100%;
      padding: 10px 12px;
      border: 2px solid #008000;
      border-radius: 8px;
      outline: none;
      transition: border 0.3s ease;
    }

    .input-group input:focus {
      border-color: #6a0dad;
    }

    .toggle-password {
      position: absolute;
      top: 50%;
      right: 12px;
      transform: translateY(-50%);
      cursor: pointer;
      font-size: 0.9rem;
      color: #008000;
    }

    .register-btn {
      width: 100%;
      background: #008000;
      color: white;
      padding: 0.8rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .register-btn:hover {
      background: #6a0dad;
    }

    .bottom-text {
      text-align: center;
      margin-top: 1rem;
      font-size: 0.9rem;
    }

    .bottom-text a {
      color: #008000;
      text-decoration: none;
    }

    @keyframes slideIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="register-container">
    <h2>Create Account</h2>
    <form onsubmit="handleRegister(event)">
      <div class="input-group">
        <label for="fullname">Full Name</label>
        <input type="text" id="fullname" required />
      </div>
      <div class="input-group">
        <label for="email">Email</label>
        <input type="email" id="email" required />
      </div>
      <div class="input-group">
        <label for="password">Password</label>
        <input type="password" id="password" required />
        <span class="toggle-password" onclick="togglePassword()">view</span>
      </div>
      <button type="submit" class="register-btn">Register</button>
    </form>
    <div class="bottom-text">
      Already have an account? <a href="login.html">Login</a>
    </div>
  </div>

  <script>
    function togglePassword() {
      const passwordInput = document.getElementById("password");
      const toggle = document.querySelector(".toggle-password");
      if (passwordInput.type === "password") {
        passwordInput.type = "text";
        toggle.textContent = "view";
      } else {
        passwordInput.type = "password";
        toggle.textContent = "view";
      }
    }

    function handleRegister(event) {
      event.preventDefault();
      alert("Account created!");
      // Add backend logic or storage logic here
    }
  </script>
</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Login Page</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet"/>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      height: 100vh;
      background: linear-gradient(to bottom right, #6a0dad, #ffffff, #008000);
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .login-container {
      background: white;
      padding: 2.5rem;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
      width: 350px;
      animation: fadeIn 1s ease-in-out;
    }

    .login-container h2 {
      text-align: center;
      margin-bottom: 1.5rem;
      color: #6a0dad;
    }

    .input-group {
      margin-bottom: 1.2rem;
      position: relative;
    }

    .input-group label {
      display: block;
      margin-bottom: 0.4rem;
      color: #008000;
    }

    .input-group input {
      width: 100%;
      padding: 10px 12px;
      border: 2px solid #6a0dad;
      border-radius: 8px;
      outline: none;
      transition: border 0.3s ease;
    }

    .input-group input:focus {
      border-color: #008000;
    }

    .toggle-password {
      position: absolute;
      top: 50%;
      right: 12px;
      transform: translateY(-50%);
      cursor: pointer;
      font-size: 0.9rem;
      color: #6a0dad;
    }

    .login-btn {
      width: 100%;
      background: #6a0dad;
      color: white;
      padding: 0.8rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .login-btn:hover {
      background: #008000;
    }

    .bottom-text {
      text-align: center;
      margin-top: 1rem;
      font-size: 0.9rem;
    }

    .bottom-text a {
      color: #6a0dad;
      text-decoration: none;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form onsubmit="handleLogin(event)">
      <div class="input-group">
        <label for="username">Username</label>
        <input type="text" id="username" required />
      </div>
      <div class="input-group">
        <label for="password">Password</label>
        <input type="password" id="password" required />
        <span class="toggle-password" onclick="togglePassword()">view</span>
      </div>
      <button type="submit" class="login-btn">Log In</button>
    </form>
    <div class="bottom-text">
      Don't have an account? <a href="#">Register</a>
    </div>
  </div>

  <script>
    function togglePassword() {
      const passwordInput = document.getElementById("password");
      const toggle = document.querySelector(".toggle-password");
      if (passwordInput.type === "password") {
        passwordInput.type = "text";
        toggle.textContent = "view";
      } else {
        passwordInput.type = "password";
        toggle.textContent = "view";
      }
    }

    function handleLogin(event) {
      event.preventDefault();
      alert("Logging in...");
      // Here you can add login authentication logic
    }
  </script>
</body>
</html>
