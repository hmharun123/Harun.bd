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
