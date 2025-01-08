activity6


<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sign Up</title>
</head>
<body>
  <h2>Sign Up</h2>
  <p>Please fill in this form to create an account!</p>
  <form action="login.html" method="POST">
    <label for="username">Username:</label><br>
    <input type="text" id="username" name="username" placeholder="Enter your username" required><br><br>
    
    <label for="email">Email Address:</label><br>
    <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
    
    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
    
    <label for="confirm_password">Confirm Password:</label><br>
    <input type="password" id="confirm_password" name="confirm_password" placeholder="Confirm your password" required><br><br>
    
    <input type="checkbox" id="terms" name="terms" required>
    <label for="terms">
      I accept the <a href="#">Terms of Use</a> & <a href="#">Privacy Policy</a>
    </label><br><br>
    
    <button type="submit">Sign Up</button>
  </form>
  <p>Already have an account? <a href="login.html">Sign In</a></p>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form with HTML5 Elements</title>
</head>
<body>
  <h2>Form with HTML5 Elements</h2>
  
  <form action="#" method="POST">
    <!-- Text Box -->
    <label for="textbox">Text Box:</label>
    <input type="text" id="textbox" name="textbox" placeholder="Enter text here" required><br><br>
    
    <!-- Radio Buttons -->
    <fieldset>
      <legend>Radio Buttons:</legend>
      <input type="radio" id="radio1" name="radioGroup" value="Option1" required>
      <label for="radio1">Option 1</label><br>
      <input type="radio" id="radio2" name="radioGroup" value="Option2">
      <label for="radio2">Option 2</label><br>
      <input type="radio" id="radio3" name="radioGroup" value="Option3">
      <label for="radio3">Option 3</label><br>
    </fieldset><br>
    
    <!-- Check Boxes -->
    <fieldset>
      <legend>Check Boxes:</legend>
      <input type="checkbox" id="checkbox1" name="checkboxGroup" value="Check1">
      <label for="checkbox1">Check 1</label><br>
      <input type="checkbox" id="checkbox2" name="checkboxGroup" value="Check2">
      <label for="checkbox2">Check 2</label><br>
      <input type="checkbox" id="checkbox3" name="checkboxGroup" value="Check3">
      <label for="checkbox3">Check 3</label><br>
    </fieldset><br>
    
    <!-- Selection Box with size -->
    <label for="selection">Selection Box (size 3):</label>
    <select id="selection" name="selection" size="3">
      <option value="Option1">Option 1</option>
      <option value="Option2">Option 2</option>
      <option value="Option3">Option 3</option>
      <option value="Option4">Option 4</option>
    </select><br><br>
    
    <!-- Option Box (Drop-down) -->
    <label for="dropdown">Option Box:</label>
    <select id="dropdown" name="dropdown">
      <option value="Option1">Option 1</option>
      <option value="Option2">Option 2</option>
      <option value="Option3">Option 3</option>
    </select><br><br>
    
    <!-- TextArea Box -->
    <label for="textarea">TextArea Box:</label><br>
    <textarea id="textarea" name="textarea" rows="4" cols="30" placeholder="Enter your comments"></textarea><br><br>
    
    <!-- Datalist -->
    <label for="datalistInput">Datalist:</label>
    <input list="options" id="datalistInput" name="datalistInput">
    <datalist id="options">
      <option value="Option 1">
      <option value="Option 2">
      <option value="Option 3">
    </datalist><br><br>
    
    <!-- Submit Button -->
    <button type="submit">Submit</button>
  </form>
</body>
</html>

activity7

<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>About Me</title>
 <style>
 body {
 font-family: Arial, sans-serif;
 color: black;
 background-color: #c2c0f2;
 margin: 0;
 padding: 0;
 }
 h1 {
 text-align: center;
 color: #2b2b70;
 margin-top: 20px;
 }
 h2 {
 text-align: center;
 font-style: italic;
 color: #4040b2;
 }
 .highlight {
 font-weight: bold;
 color: #706dcd;
 }
 p {
 text-align: justify;
 margin: 20px auto;
 width: 60%;
 }
 img {
 float: left;
 margin: 0 20px 10px 0;
 border-radius: 8px;
 border: 2px solid #706dcd;
 width: 120px;
 height: auto; }
 strong {
 font-weight: bold;
 }
 em {
 font-style: italic;
 }
 </style>
</head>
<body>
 <!-- name as Heading -->
 <div>
   <h1>Ayuvi Chaudhary</h1>
   <h2>"Aspiring Coder"</h2>
 </div>

 <!-- Description of Yourself -->
 <div>
   <p>
     <img src="q1.jpg" alt="My Photo">
     My name is <span class="highlight">Ayuvi Chaudhary</span>. I hail from Delhi, India,
     and currently, I am pursuing my B.Tech degree in CSE from VIT Vellore, Tamil Nadu. I am
     passionate about <span class="highlight">web development and programming</span>. I
     love <strong>solving problems</strong> and creating <strong>beautiful</strong>,
     <strong>functional</strong> web applications. I believe <em>learning</em> is a
     continuous process, and I always strive to improve my skills.
   </p>
   <p>
     In my free time, I enjoy exploring <span class="highlight">new technologies</span>,
     reading books, and engaging in outdoor activities. I am a <span class="highlight">detailoriented</span> person who pays attention to design and functionality, ensuring every
     project I create meets user needs.
   </p>
   <p>
     I aim to work as a professional web developer and contribute to innovative projects
     that make a difference in people's lives. My strengths include <em>hard work</em>,
     <em>dedication</em>, and the <em>ability</em> to adapt to new challenges.
   </p>
 </div>

 <!-- Footer with a message -->
 <div style="text-align: center; margin-top: 20px;">
   <p>
     Thank you for visiting my profile! Feel free to connect with me to learn more.
   </p>
 </div>
</body>
</html>

activity8


<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Thematic Web Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background: #333;
      color: white;
      display: flex;
      justify-content: space-around;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    article, section, aside {
      padding: 20px;
    }
    section {
      margin: 20px auto;
      width: 80%;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    aside {
      background: #f9f9f9;
      margin: 20px;
      padding: 20px;
      border-left: 4px solid #4CAF50;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
    }
    footer form {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 10px;
    }
    footer form input, footer form textarea {
      width: 80%;
      margin: 5px 0;
      padding: 10px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
    footer form input[type="submit"] {
      background: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer form input[type="submit"]:hover {
      background: #45a049;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Welcome to My Thematic Web Page</h1>
    <p>Discover exciting content and more!</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#navigation">Navigation</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <!-- Home Page -->
  <section id="home">
    <article>
      <h2>About My Theme</h2>
      <p>
        This website is designed to explore various web development concepts and showcase activities. You can navigate to different sections, view blogs with multimedia, and reach out to us through the Contact Us page.
      </p>
    </article>
  </section>

  <!-- Navigation Page -->
  <section id="navigation">
    <article>
      <h2>Navigation</h2>
      <p>Here is the list of activities from Assignment 1A, 1B, and 1C:</p>
      <ul>
        <li><a href="activity1.html">Activity 1</a></li>
        <li><a href="activity2.html">Activity 2</a></li>
        <li><a href="activity3.html">Activity 3</a></li>
        <!-- Add more links as needed -->
      </ul>
    </article>
  </section>

  <!-- Blog Page -->
  <section id="blog">
    <article>
      <h2>Blog</h2>
      <p>Check out some interesting photos and videos:</p>
      <div>
        <img src="photo1.jpg" alt="Sample Photo 1" style="width:100%; border-radius:8px;">
      </div>
      <div>
        <video controls style="width:100%; margin-top:20px;">
            <source src="video.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
      </div>
      <p>Visit <a href="https://example.com" target="_blank">this website</a> for more inspiration.</p>
    </article>
  </section>

  <!-- Contact Us -->
  <footer id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <input type="submit" value="Send">
    </form>
    <p>© 2025 My Thematic Web Page</p>
  </footer>

</body>
</html>
