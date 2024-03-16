<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Kas Design</title>
  <style>
    body {
      background-color: #f5deb3;
      padding: 20px;
      margin: 0;
    }
    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px;
    }
    .menu-button {
      cursor: pointer;
      font-size: 40px;
      background-color: transparent;
      color: #97837A;
      padding: 10px;
      border-radius: 20px;
    }
    .button-container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px;
    }
    .button-container button {
      background-color: #97837A;
      color: #f5deb3;
      border: none;
      padding: 15px 30px;
      margin: 0 10px;
      border-radius: 25px;
      font-size: 20px;
    }
    .logo {
      max-width: 200px;
    }
    .line {
      width: 100%;
      height: 5px;
      background-color: #97837A;
    }
    .image-container {
      display: flex;
      flex-wrap: wrap;
    }
    .image-container img {
      width: 100%;
      margin-top: 20px;
    }
  </style>
</head>

<body>
  <header>
    <img class="logo" src="Kas Design logo.png" alt="Logo">
    <div class="menu-button">&#9776;</div>
  </header>

  <div class="button-container">
    <button>My work</button>
    <button>About me</button>
    <button>Contact</button>
    <button>Socials</button>
  </div>

  <div class="line"></div>

  <div class="image-container">
    <!-- Add the textbox image -->
    <img src="Text-Where Ideas, become a reality.png" alt="Textbox Image">
    <!-- Add the map image -->
    <img src="Global design.png" alt="Map Image">
  </div>

  <!-- More content or footer goes here -->
</body>
</html>
