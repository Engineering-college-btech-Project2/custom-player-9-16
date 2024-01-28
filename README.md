# window.alert()

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Custom Video Player</title>
   <link rel="icon" href="https://raw.githubusercontent.com/akashdip2001/website-2/main/images/favicon.jpg?token=GHSAT0AAAAAACMGYPVOP4ZUPUDP4Q2FKSEWZNNHMWA">

  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #1a1a1a;
      color: #fff;
      font-family: Arial, sans-serif;
    }

    #video-container {
      position: relative;
      width: 100%;
      padding-bottom: 177.78%; /* 9:16 aspect ratio */
      overflow: hidden;
    }

    #custom-video {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }

    #continue-button {
      position: fixed;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
      padding: 10px 20px;
      background-color: #3498db;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
    }


    .login-button {
    position: fixed;
    top: 20px;
    right: 20px;
    padding: 10px 20px;
    background-color: transparent;
    color: white;
    border: 2px solid rgba(255, 255, 255, 0.5); /* Transparent white border */
    border-radius: 5px;
    font-weight: bold;
    text-decoration: none;
    text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.5); /* Shadow effect */
    transition: border-color 0.3s, color 0.3s, text-shadow 0.3s;
}

.login-button:hover {
    border-color: white; /* White border on hover */
    color: #f0f0f0; /* Lighter white color on hover */
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.8); /* Enhanced shadow effect on hover */
}

  </style>
</head>
<body>

  <div id="video-container">
    <iframe id="custom-video" width="100%" height="100%" src="https://www.youtube.com/embed/yiEQOujkESA?rel=0" frameborder="0" allowfullscreen sandbox="allow-same-origin allow-scripts"></iframe>
  </div>

  <a href="https://engineering-college-btech.github.io/freecad-videos/" id="continue-button">Continue</a>

  <a href="http://freecadapp2.000.pe/login.php" class="login-button">Log Out</a>

  <script>
    window.onload = function() {
  if (window.innerWidth <= 768) {
    window.alert("✅ plz watch the video first \n✅ then click continue \n\n ✅ and এই website টার ব্যেপারে college এ কোনো sir বা maam যেন না যানতে পারে");
  }
      
   if (window.innerWidth > 768) {
    window.location.href = '404.html';
  }
 
};

    // Prevent redirection when clicking on the video
    document.getElementById('custom-video').addEventListener('click', function (event) {
      event.preventDefault();
    });
  </script>
       <script src="https://www.youtube.com/iframe_api"></script>

</body>
</html>
```

# custom popup message on a dark theme

```html

```
