# a-normal-creative-making-website
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agency</title>
  <link rel="stylesheet" href="./solution.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
</head>

<body>
  <div class="main">
    <img class="logo" src="./assets/images/logo.png" alt="logo">
    <h1>We are a <span class="creative">Creative</span> <br />Design Agency</h1>
    <div class="left card"><img class="tile-image" src="./assets/images/beautiful.jpg" alt="hand and flower in water">
      <h2 class="card-title">Beauty</h2>
      <p class="card-text">We strive to create the most beautiful websites for all your needs. Working closely with you
        to
        design and
        develop an amazing website for your business.</p>
    </div>

    <div class="right card"><img class="tile-image" src="./assets/images/construction.jpg" alt="metal structure">
      <h2 class="card-title">Construction</h2>
      <p>Built by our team of professional developers, we ensure the most rigourous and modern websites. Built from
        scratch using HTML and CSS. Only the best for you.</p>
    </div>

  </div>
  <footer>
    <p>Create. Develop. Design.</p>
  </footer>
</body>

</html>
#this whole is to saved in a file containing extension .html 
# now thi below code is for style.css extension file
body {
  font-family: "Poppins", sans-serif;
  margin: 50px 50px 0 50px;
  background-color: #faf9f6;
  display: flex;
  flex-direction: column;
  min-height: 95vh;
}
.main {
  flex: 1;
}

h1 {
  font-size: 5rem;
}

footer {
  text-align: right;
  color: midnightblue;
}

.tile-image {
  height: 200px;
  float: left;
  margin-right: 50px;
}

.card {
  width: 45%;
}

.left {
  float: left;
}

.right {
  float: right;
}

.creative {
  color: midnightblue;
}

@media (max-width: 680px) {
  .logo {
    width: 100px;
  }

  h1 {
    font-size: 3.5rem;
    text-align: center;
  }

  .card {
    width: 100%;
    display: block;
    margin-bottom: 30px;
    text-align: justify;
  }

  .card img {
    margin-bottom: 10px;
    width: 100%;
    display: inline;
    object-fit: cover;
  }
}

