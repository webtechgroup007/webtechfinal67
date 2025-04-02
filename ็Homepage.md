<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap 5 Website Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <style>
  .fakeimg {
    height: 200px;
    background: #aaa;
  }
  </style>
</head>
<body>

<div class="p-5 bg-primary text-white text-center">
  <h1>About Me</h1>
  <p>Let's go!</p> 
</div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <div class="container-fluid">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link active" href="bt-template.html" >About Me</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="time table.html">Time Table</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="myplace.html">My Place</a>
      </li>
      
    </ul>
  </div>
</nav>

<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
      <h2>About Me</h2>
      <h5>Photo of me:</h5>
      <img src="img/IMG_9506.JPG" width="350" alt="แมวส้มขาสั้น" height="200">
      <p>Hello! My name is Beem, and I am a web developer with a passion for creating beautiful and responsive websites. 
        I specialize in front-end development using HTML, CSS, and JavaScript. In my free time, I enjoy exploring new technologies, 
        traveling, and learning about different cultures.</p>
      
      <hr class="d-sm-none">
    </div>
    <div class="col-sm-8">
      <h2>With friends</h2>
      <h5>FEB 21, 2025</h5>
      <img src="img/IMG_9522.JPG" width="350" alt="แมวส้มขาสั้น" height="220">
      
      
    </div>
  </div>
</div>



</body>
</html>
