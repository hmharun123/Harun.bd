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
    .section {
  padding: 20px;
  background-color: #f4f8fb;
  border-radius: 10px;
  max-width: 800px;
  margin: 30px auto;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

.section h2 {
  font-size: 24px;
  margin-bottom: 20px;
  color: #2c3e50;
}

.section p {
  margin: 5px 0;
  font-size: 16px;
  color: #333;
}
.social-order-section {
  text-align: center;
  padding: 20px;
}

.social-order-section h2,
.social-order-section h3 {
  color: #2c3e50;
  margin-bottom: 15px;
}

.order-buttons,
.social-buttons {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-bottom: 20px;
}

.btn {
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  border-radius: 30px;
  color: #fff;
  text-decoration: none;
  display: flex;
  align-items: center;
  gap: 8px;
  transition: transform 0.2s ease;
}

.btn:hover {
  transform: scale(1.05);
}

/* Individual Button Colors */
.email {
  background-color: #007BFF;
}

.whatsapp {
  background-color: #25D366;
}

.fiverr {
  background-color: #1DBF73;
}

.facebook {
  background-color: #3b5998;
}

.instagram {
  background-color: #E1306C;
}

.tiktok {
  background-color: #010101;
}

.whatsapp-alt {
  background-color: #128C7E;
}
.certificate-section,
.media-section,
.image-row,
.gallery-section {
  text-align: center;
  margin: 40px 20px;
}

.certificate-section img,
.media-section img,
.image-row img,
.gallery img {
  margin: 10px;
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.media-photo {
  width: 300px;
}

.media-video {
  width: 400px;
  margin-top: 20px;
  border-radius: 10px;
}

.image-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}

.image-row img {
  width: 150px;
  height: auto;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
  padding: 10px;
}

.gallery img {
  width: 100%;
  height: auto;
  border-radius: 12px;
}
.section {
  padding: 30px;
  text-align: center;
}

.portfolio-list {
  list-style: none;
  padding: 0;
  margin-top: 15px;
}

.portfolio-list li {
  margin: 10px 0;
}

.portfolio-list a {
  text-decoration: none;
  color: #444;
  font-weight: bold;
}

.links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin-top: 30px;
}

.btn {
  padding: 10px 20px;
  color: #fff;
  font-weight: bold;
  text-decoration: none;
  border-radius: 10px;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-size: 16px;
  transition: background 0.3s;
}

.btn i {
  font-size: 18px;
}

/* Color Variants */
.blue { background-color: #1877F2; }
.red { background-color: #FF0000; }
.darkgreen { background-color: #25D366; }
.purple { background-color: #C13584; }
.pink { background-color: #FF69B4; }
.green { background-color: #1DBF73; }

.btn:hover {
  opacity: 0.9;
}

.icon {
  width: 20px;
  height: auto;
}
  </style>
  <!-- Google CSE Script -->
  <script async src="https://cse.google.com/cse.js?cx=d3251f7aa5ee247d5"></script>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
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
<section id="home" class="section active">
  <h2>Welcome to My Profile</h2>
  <div style="display: flex; flex-wrap: wrap; align-items: center; gap: 20px;">
    <img src="harun.jpg" alt="Harun's Photo" class="profile" style="width: 180px; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);" />
    
    <div>
      <p><strong>Name:</strong> Md. Harun Or Rashid</p>
      <p><strong>Address:</strong> Manikganj, Dhaka, Bangladesh</p>
      <p><strong>Email:</strong> <a href="mailto:hmharun796@gmail.com">hmharun796@gmail.com</a></p>
      <p><strong>Education:</strong> SSC, Lemubari Binoda Sundori High School</p>
      <p><strong>Profession:</strong> Freelancer</p>
      <p><strong>Skills:</strong> Data Entry, E-commEntry, Web Research, Data Research, Web Scraping, Data Scraping, Copy-Paste, and more.</p>
      <p><strong>Phone 1:</strong> <a href="tel:+8801648131500">+8801648131500</a></p>
      <p><strong>Phone 2:</strong> <a href="tel:+8801316888404">+8801316888404</a></p>
    </div>
  <div class="social-order-section">

  <h2>Hire Me or Connect with Me</h2>

  <div class="order-buttons">
    <a href="mailto:harunrm900@gmail.com?subject=Hiring%20Request&body=Hello,%20I%20would%20like%20to%20hire%20you%20for%20a%20project." target="_blank" class="btn email">
      <i class="fas fa-envelope"></i> Order Now (Email)
    </a>
    <a href="https://wa.me/8801648131500?text=Hi%20Harun,%20I%20am%20interested%20in%20your%20services." target="_blank" class="btn whatsapp">
      <i class="fab fa-whatsapp"></i> Order on WhatsApp
    </a>
  </div>

  <h3>Connect on Social Media</h3>

  <div class="social-buttons">
    <a class="btn fiverr" href="https://www.fiverr.com/s/dDlW3G3" target="_blank"><i class="fas fa-briefcase"></i> Fiverr</a>
    <a class="btn facebook" href="https://www.facebook.com/share/r/1BcEg68nzy/" target="_blank"><i class="fab fa-facebook-f"></i> Facebook</a>
    <a class="btn instagram" href="https://www.instagram.com/p/DIeAfFXT_oO/" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
    <a class="btn tiktok" href="https://www.tiktok.com/@user6071584366187" target="_blank"><i class="fab fa-tiktok"></i> TikTok</a>
    <a class="btn whatsapp-alt" href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
  </div>
<!-- Certificate Section -->
<div class="certificate-section">
  <h2>Certificate of Completion</h2>
  <img src="certificate.jpg" alt="Certificate" />
  <img src="file_000000004bd461f89c7906893d08c772.png" alt="Certificate" />
</div>

<!-- Photo & Video Section -->
<div class="media-section">
  <h2>My Photo & Video</h2>
  <img src="media/myphoto.jpg" alt="My Photo" class="media-photo" />
  <video controls class="media-video">
    <source src="media/Ami_Soia_Geleo_Soibena_Bidhata.mp4" type="video/mp4" />
    Your browser does not support the video tag.
  </video>
</div>

<!-- Image Row -->
<div class="image-row">
  <img src="data-antry.png" alt="Data Entry" />
  <img src="file_00000000875861f990b4e5fffbcbb32e.png" alt="Certificate" />
  <img src="312.jpg" alt="Certificate" />
  <img src="076ac6.jpg" alt="076ac6" />
  <img src="SAMPLE.jpeg" alt="Sample" />
  <img src="data.jpg" alt="Data" />
</div>

<!-- Gallery Section -->
<div class="gallery-section">
  <h2>My Gallery</h2>
  <div class="gallery">
    <img src="076ac6.jpg" alt="Photo 1" />
    <img src="media/photo2.jpg" alt="Photo 2" />
    <img src="media/photo3.jpg" alt="Photo 3" />
    <img src="media/photo4.jpg" alt="Photo 4" />
  </div>
<!-- YouTube Section -->
<section class="section">
  <h2>My YouTube Channel</h2>
  <p>Subscribe to my channel for tutorials, tips, and more!</p>
  <a class="btn red" href="https://youtube.com/@mdharun-n6j" target="_blank">
    <i class="fa-brands fa-youtube"></i> Visit My YouTube
  </a>
</section>

<!-- Portfolio Section -->
<section class="section portfolio-section">
  <h2>My Portfolio</h2>
  <ul class="portfolio-list">
    <li><a href="https://docs.google.com/spreadsheets/d/1FSV3CzDlRSDJHaumYrCcvKFcBKGedUhFU9qPDY6viW4/edit?usp=drivesdk" target="_blank">Sample Data Entry Work</a></li>
    <li><a href="https://drive.google.com/file/d/1xA2EXAMPLE123/view" target="_blank">Product Listing (Excel)</a></li>
    <li><a href="https://drive.google.com/file/d/1yB3EXAMPLE456/view" target="_blank">Web Research Sample</a></li>
    <li><a href="https://drive.google.com/file/d/1zC4EXAMPLE789/view" target="_blank">PDF to Excel Conversion</a></li>
  </ul>
</section>

<!-- Social Media Links -->
<section class="links">
  <a href="https://www.facebook.com/share/r/1BcEg68nzy/" class="btn blue" target="_blank">
    <i class="fa-brands fa-facebook-f"></i> Facebook
  </a>
  <a href="https://youtube.com/@mdharun-n6j" class="btn red" target="_blank">
    <i class="fa-brands fa-youtube"></i> YouTube
  </a>
  <a href="https://wa.me/8801648131500?text=Hi,%20I%20want%20to%20contact%20you" class="btn darkgreen" target="_blank">
    <i class="fa-brands fa-whatsapp"></i> WhatsApp
  </a>
  <a href="https://www.instagram.com/p/DIeAfFXT_oO/" class="btn purple" target="_blank">
    <i class="fa-brands fa-instagram"></i> Instagram
  </a>
  <a href="https://www.tiktok.com/@user6071584366187" class="btn pink" target="_blank">
    <i class="fa-brands fa-tiktok"></i> TikTok
  </a>
  <a href="https://www.fiverr.com/s/dDlW3G3" class="btn green" target="_blank">
    <img src="fiverr-logo.png" alt="Fiverr" class="icon" /> Fiverr
  </a>

</section>
</body>
</html>
