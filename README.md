<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Harun's Personal Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Three dot menu */
    .menu-toggle {
      position: absolute;
      top: 20px;
      right: 20px;
      cursor: pointer;
      font-size: 24px;
      padding: 10px;
    }

    .menu-content {
      display: none;
      position: absolute;
      top: 60px;
      right: 20px;
      background-color: #f9f9f9;
      border: 1px solid #ccc;
      border-radius: 5px;
      z-index: 1000;
      min-width: 180px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    .menu-content a {
      display: block;
      padding: 10px;
      color: #333;
      text-decoration: none;
    }

    .menu-content a:hover {
      background-color: #eee;
    }

    .section {
      padding: 20px;
    }

    /* Google search bar style */
    .gcse-search {
      margin: 20px auto;
      max-width: 600px;
    }
  </style>
  <!-- Google CSE Script -->
  <script async src="https://cse.google.com/cse.js?cx=d3251f7aa5ee247d5"></script>
</head>
<body>

  <!-- Three dot button -->
  <div class="menu-toggle" onclick="toggleMenu()">☰</div>

  <!-- Menu content -->
  <div class="menu-content" id="menu">
    <a href="#" onclick="showSection('profile')">Profile</a>
    <a href="#" onclick="showSection('privacy')">Privacy Policy</a>
    <a href="#" onclick="showSection('contact')">Contact</a>
    <a href="#" onclick="showSection('about')">About</a>
    <a href="#" onclick="showSection('settings')">Settings</a>
    <a href="#" onclick="showSection('certificate')">Certificates</a>
    <a href="#" onclick="showSection('media')">Tutorial</a>
    <a href="assets/Harun_CV.pdf" download>Download CV</a>
    <a href="mailto:hmharun796@gmail.com?subject=Hello&body=I want to connect with you.">Send Email</a>
  </div>

  <!-- Google Search Bar always visible on homepage -->
  <div class="gcse-search"></div>

  <!-- Sections -->
  <div id="profile" class="section">
    <h2>Profile</h2>
    <p>I am Md. Harun Or Rashid, a skilled and dedicated professional specializing in data entry, web research, and PDF to Excel conversions...</p>
  </div>

  <div id="privacy" class="section" style="display:none">
    <h2>Privacy Policy</h2>
    <p>All information collected through this site is used solely to improve user experience...</p>
  </div>

  <div id="contact" class="section" style="display:none">
    <h2>Contact</h2>
    <p>Email: hmharun796@gmail.com<br>Phone: +880 1648-131500<br>
    Facebook: <a href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit</a><br>
    WhatsApp: <a href="https://wa.me/8801648131500" target="_blank">Chat</a></p>
  </div>

  <div id="about" class="section" style="display:none">
    <h2>About</h2>
    <p>I'm passionate about providing efficient data entry and digital solutions...</p>
  </div>

  <div id="settings" class="section" style="display:none">
    <h2>Settings</h2>
    <p>Website Theme: Default<br>Language: English<br>Notifications: Enabled</p>
  </div>

  <div id="certificate" class="section" style="display:none">
    <h2>Certificates</h2>
    <ul>
      <li><img src="file_00000000875861f990b4e5fffbcbb32e.png" alt="Certificate 1" width="200" /></li>
      <li><img src="312.jpg" alt="Certificate 2" width="200" /></li>
      <li><img src="076ac6.jpg" alt="Certificate 3" width="200" /></li>
    </ul>
  </div>

  <div id="media" class="section" style="display:none">
    <h2>Tutorial</h2>
    <video controls width="320">
      <source src="video.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
    <p><a href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube Channel</a></p>
  </div>

  <script>
    function toggleMenu() {
      var menu = document.getElementById("menu");
      menu.style.display = (menu.style.display === "block") ? "none" : "block";
    }

    function showSection(id) {
      var sections = document.getElementsByClassName("section");
      for (var i = 0; i < sections.length; i++) {
        sections[i].style.display = "none";
      }
      document.getElementById(id).style.display = "block";
    }
  </script>

</body>
</html>
