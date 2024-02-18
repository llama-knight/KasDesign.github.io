
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Kas Design</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      background-color: #f5deb3;
      padding-left: 20px;
    }
    .separator {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: -5px;
    }
    .separator::before {
      content: "\2605";
      color: #97837A;
      font-size: 40px;
      margin-right: 10px;
    }
    header {
      padding: 10px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      position: relative;
    }
    .menu-button {
      cursor: pointer;
      font-size: 70px;
      background-color: transparent;
      color: #97837A;
      margin-left: auto;
      margin-top: -10px;
      padding: 20px 60px;
      border-radius: 20px;
    }
    .button-container {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      margin-left: 300px;
    }
    .button-container button {
      background-color: #97837A;
      color: #f5deb3;
      border: none;
      padding: 25px 70px;
      margin: 0 30px;
      border-radius: 25px;
      font-size: 25px;
    }
    .logo {
      /* margin-right: auto; */
    }
    .line {
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 100%;
      height: 5px;
      background-color: #97837A;
    }
    .textbox-image, .map-image {
      background-color: transparent;
    }
    .textbox-image {
      width: 40%; /* Adjust the width as needed */
      margin-top: 20px; /* Adjust the margin-top as needed */
    }
    .map-image {
      width: 50%; /* Adjust the width as needed */
      margin-top: -150px; /* Adjust the margin-top as needed */
      margin-left: 500px;
    }
  </style>
</head>

<body>
  <header>
    <img class="logo" src="Kas%20design%20logo.png" alt="Kas design Logo" style="background-color: transparent;">
    <div class="button-container">
      <button>My work</button>
      <div class="separator"></div>
      <button>About me</button>
      <div class="separator"></div>
      <button>Contact</button>
      <div class="separator"></div>
      <button>Socials</button>
    </div>
    <div class="menu-button">&#9776;</div>
    <div class="line"></div>
  </header>

  <!-- Add the textbox image above the map image -->
  <img class="textbox-image" src="Text-Where Ideas, become a reality.png" alt="Textbox Image" style="background-color: transparent;">

  <!-- Add the map image under the textbox image -->
  <img class="map-image" src="Global design.png" alt="Map Image" style="background-color: transparent;">

  <!-- More content or footer goes here -->
</body>
</html>

# KasDesign.github.io