<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Three Dot Menu with Google Search</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    /* থ্রি ডট বাটন স্টাইল */
    #menuBtn {
      font-size: 30px;
      cursor: pointer;
      background: transparent;
      border: none;
      position: fixed;
      top: 20px;
      right: 20px;
      z-index: 1001;
    }
    #menu {
      display: none;
      position: fixed;
      top: 60px;
      right: 20px;
      background: #fff;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
      padding: 15px;
      border-radius: 8px;
      width: 280px;
      z-index: 1000;
    }
    #menu a {
      display: block;
      padding: 8px 0;
      text-decoration: none;
      color: #333;
      border-bottom: 1px solid #eee;
    }
    #menu a:last-child {
      border-bottom: none;
    }
    #menu a:hover {
      background-color: #f0f0f0;
    }
    .section {
      display: none;
      margin-top: 80px;
      padding: 15px;
      border: 1px solid #ddd;
      border-radius: 8px;
      max-width: 600px;
    }
    .section.active {
      display: block;
    }
   /* Google Search Bar Container */
    #menu .gcse-search {
      margin-top: 15px;
    }
  </style>
</head>
<body>

  <!-- থ্রি ডট বাটন -->
  <button id="menuBtn" title="Open menu">⋮</button>

  <!-- মেনু -->
  <div id="menu">
    <a href="#" onclick="showSection('profile'); return false;">Profile</a>
    <a href="#" onclick="showSection('privacy'); return false;">Privacy Policy</a>
    <a href="#" onclick="showSection('contact'); return false;">Contact</a>
    <a href="#" onclick="showSection('about'); return false;">About</a>
    <a href="#" onclick="showSection('settings'); return false;">Settings</a>
    <a href="#" onclick="showSection('certificate'); return false;">Certificates</a>
    <a href="#" onclick="showSection('media'); return false;">Tutorial</a>
    <a href="assets/Harun_CV.pdf" download>Download CV</a>
    <a href="mailto:hmharun796@gmail.com?subject=Hello&body=I want to connect with you.">Send Email</a>
  
   <div id="profile" class="section">
     <h2>Profile</h2>
      <p>I am Md. Harun Or Rashid, a skilled and dedicated professional specializing in data entry, web research, and PDF to Excel conversions. I also create Payoneer account tutorials and provide project-based services through platforms like Fiverr.</p>
  </div>

  <div id="privacy" class="section">
    <h2>Privacy Policy</h2>
    <p>All information collected through this site is used solely to improve user experience and will not be shared with third parties. You may contact me for any concerns about your data privacy.</p>
  </div>

  <div id="contact" class="section">
    <h2>Contact</h2>
    <p>
      Email: hmharun796@gmail.com<br />
      Phone: +880 1648-131500<br />
      Facebook: <a href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank">Visit My Facebook</a><br />
      WhatsApp: <a href="https://wa.me/8801648131500" target="_blank">Chat on WhatsApp</a>
    </p>
  </div>

  <div id="about" class="section">
    <h2>About</h2>
    <p>I'm passionate about providing efficient data entry and digital solutions. My goal is to ensure client satisfaction through quality work and timely delivery. I also manage a YouTube channel for educational content.</p>
  </div>

  <div id="settings" class="section">
    <h2>Settings</h2>
    <p>
      Website Theme: Default<br />
      Language: English<br />
      Notifications: Enabled<br />
      <em>(Settings options can be expanded based on development needs)</em>
    </p>
  </div>

  <div id="certificate" class="section">
    <h2>Certificates</h2>
    <ul>
      <li><img src="file_00000000875861f990b4e5fffbcbb32e.png" alt="Certificate 1" width="200" /></li>
      <li><img src="312.jpg" alt="Certificate 2" width="200" /></li>
      <li><img src="076ac6.jpg" alt="Certificate 3" width="200" /></li>
    </ul>
  </div>

  <div id="media" class="section">
    <h2>Tutorial</h2>
    <p>Watch my video tutorials on YouTube:</p>
    <video controls width="320">
      <source src="video.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
    <p><a href="https://youtube.com/@mdharun-n6j" target="_blank">Visit My YouTube Channel</a></p>
  </div>

  <script>
    const menuBtn = document.getElementById('menuBtn');
    const menu = document.getElementById('menu');

    menuBtn.addEventListener('click', () => {
      if (menu.style.display === 'block') {
        menu.style.display = 'none';
      } else {
        menu.style.display = 'block';
      }
    });

    function showSection(id) {
      // Hide all sections
      document.querySelectorAll('.section').forEach(section => {
        section.classList.remove('active');
      });
      // Show selected section
      const section = document.getElementById(id);
      if(section) section.classList.add('active');

      // Hide menu after clicking link
      menu.style.display = 'none'
    </script>
   <script async src="https://cse.google.com/cse.js?cx=d3251f7aa5ee247d5"></script>
   <div class="gcse-search"></div>
  </div>
</body>
</html>
