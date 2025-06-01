<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Md. Harun Or Rashid</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
     header {
      background-color: #333;
      color: white;
      padding: 10px 20px;
      font-size: 24px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .menu-button {
      background: none;
      border: none;
      color: white;
      font-size: 24px;
      cursor: pointer;
    }
    .menu-content {
      display: none;
      background: #f0f0f0;
      padding: 10px;
    }
    .menu-content a {
      display: block;
      padding: 8px;
      text-decoration: none;
      color: #333;
    }
    .section {
      display: none;
      padding: 20px;
    }
    .section.active {
      display: block;
    }
    .profile {
      width: 150px;
      border-radius: 50%;
    }
    #contact {
  display: block;
  visibility: visible;
}
    .button {
      display: inline-block;
      margin: 5px;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
    .button.fiverr {
      background-color: #1dbf73;
    }
    .image-row img {
      width: 100px;
      margin: 5px;
      border-radius: 5px;
    }
    .gallery img {
      width: 120px;
      margin: 10px;
      border-radius: 8px;
    }
    .certificate-section img {
      width: 300px;
      margin: 10px 0;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    #backToTop {
      display: none;
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #333;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 50%;
      font-size: 20px;
      cursor: pointer;
    }
    <style>
  .menu-button {
    font-size: 24px;
    cursor: pointer;
    background: none;
    border: none;
    color: #333;
  }
.menu-content {
    display: none;
    position: absolute;
    right: 10px;
    top: 50px;
    background-color: white;
    border: 1px solid #ccc;
    z-index: 1000;
    padding: 10px;
    box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
  }
 .menu-content a {
    display: block;
    padding: 8px;
    color: #000;
    text-decoration: none;
  }
 .menu-content a:hover {
    background-color: #f2f2f2;
  }
    .menu-content {
      display: none;
      background: #f0f0f0;
      padding: 10px;
    }
background-color: #333;
      color: white;
      padding: 15px;
      font-size: 24px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #222;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 10px 15px;
      text-decoration: none;
    }
    nav a:hover {
      background: #444;
    }
    .section {
      padding: 20px;
      margin: 10px;
      background: white;
      border-radius: 8px;
    }
    .btn {
      display: inline-block;
      padding: 10px 15px;
      background: #007bff;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
    .certificate-section img {
      width: 200px;
      margin: 10px;
      border-radius: 8px;
    }
    .footer {
      text-align: center;
      background: #333;
      color: white;
      padding: 15px;
    }
    .image-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
  margin-top: 20px;
}
.image-row img {
  width: 150px;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
}
 /* Navigation */
nav {
  background-color: #2c3e50;
  padding: 15px;
  text-align: center;
  position: sticky;
  top: 0;
  z-index: 999;
}
nav a {
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover {
  color: #1abc9c;
}
.btn {
  display: inline-block;
  background-color: #1abc9c;
  color: #fff;
  padding: 8px 15px;
  border-radius: 5px;
  text-decoration: none;
}
.btn:hover {
  background-color: #16a085;
}
/* Section Styling */
.section {
  padding: 50px 20px;
  max-width: 1000px;
  margin: auto;
  background-color: #fff;
  margin-bottom: 20px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
.section h2 {
  color: #2c3e50;
  margin-bottom: 15px;
}
.section p,
.section li,
.section blockquote {
  margin-bottom: 15px;
}
/* Image Row */
.image-row {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
  margin-top: 15px;
}
.image-row img {
  max-width: 150px;
  border-radius: 8px;
  border: 2px solid #ddd;
  transition: transform 0.3s;
}
.image-row img:hover {
  transform: scale(1.05);
}
/* Project Links */
.project-links {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-top: 15px;
}
.project-links a {
  color: #1abc9c;
  text-decoration: none;
  font-weight: bold;
}
.project-links a:hover {
  text-decoration: underline;
}
/* Contact Form */
form input,
form textarea,
form button {
  width: 100%;
  padding: 10px;
  margin-top: 10px;
  border-radius: 5px;
  border: 1px solid #ccc;
  font-size: 16px;
}
form button {
  background-color: #1abc9c;
  color: white;
  border: none;
  cursor: pointer;
}
form button:hover {
  background-color: #16a085;
}
