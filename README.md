# Brand_Website
# HTML code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Font awesome icon (links) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">    
    <!-- Styling css file -->
    <link rel="Website Icon" href="website icon.jpg" type="jpg">
    <script src="./FontAwesome files/fontawesome.js"></script>
    <link rel="stylesheet" href="header.css" />
    <title>Responsive header</title>
</head>
<body>
    <script>
      const toggle = () => {
        document.getElementById("nav").classList.toggle("navactive");
      };
    </script>
    <header>
      <div class="brand">
        <span id="logoIcon">
          <img src="website icon.jpg">
        </span>
        <h1>Brand</h1>
      </div>
      <span class="fa fa-bars" id="menuIcon" onclick="toggle()"></span>
      <div class="navbar" id="nav">
        <div class="searchBox">
          <input type="text" placeholder="Search here..." />
          <span class="fa fa-search" id="searchIcon"></span>
        </div>
        <ul>
          <li>
            <span class="fa fa-home" id="headIcon"></span>
            <a href="#"> Home </a>
          </li>
          <li>
            <span class="fa fa-user-circle" id="headIcon"></span>
            <a href="#"> Profile </a>
          </li>
          <li>
            <span class="fa fa-question-circle" id="headIcon"></span>
            <a href="#"> Help </a>
          </li>
          <li>
            <span class="fa fa-lock" id="headIcon"></span>
            <a href="#"> Account </a>
          </li>
          <li>
            <span class="fa fa-sign-in" id="headIcon"></span>
            <a href="#"> Signout </a>
          </li>
        </ul>
      </div>
    </header>
    <div class="header2">
    </div>
  </body>
</html>

