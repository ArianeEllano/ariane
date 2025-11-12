<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ariane's Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-image: url('background.jpg'); /* ← ilagay mo dito pangalan ng background photo mo */
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      color: #003366;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
    }

    .container {
      width: 90%;
      max-width: 700px;
      background-color: #ffffffcc; /* may kaunting transparency */
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      margin-top: 30px;
      padding: 20px;
    }

    h1, h2 {
      text-align: center;
      color: hotpink;
    }

    p {
      text-align: center;
      line-height: 1.5;
    }

    .top-photo img {
      width: 100%;
      border-radius: 10px;
    }

    .bottom-photos {
      display: flex;
      justify-content: space-between;
      margin-top: 15px;
      gap: 5px;
    }

    .bottom-photos img {
      width: 32%;
      border-radius: 10px;
    }

    .skills {
      text-align: center;
      margin-top: 15px;
    }

    .skills span {
      background-color: #cce0ff;
      padding: 6px 12px;
      border-radius: 5px;
      margin: 4px;
      display: inline-block;
      font-weight: bold;
    }

    .contact {
      text-align: center;
      margin-top: 20px;
      background-color: #f0f8ff;
      padding: 10px;
      border-radius: 8px;
    }

    .contact a {
      color: #0059b3;
      text-decoration: none;
      font-weight: bold;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
      color: #333;
    }
  </style>
</head>

<body>
  <div class="container">
    <h1>Ariane Ellano</h1>
    <p><em>Grade 11 ICT Student</em></p>

    <div class="top-photo">
      <img src="received_853246293864285.jpeg" alt="Ariane">
    </div>

    <h2>About Me</h2>
    <p>
      Hello everyone! I’m <strong>Ariane L. Ellano</strong>, a simple girl who loves learning new things
      and discovering the world around me. I enjoy spending time with friends and listening to music.
      I believe in staying positive, working hard, and always being kind to others.
      My motto in life is: “Small steps every day lead to big dreams.”
    </p>

    <h2>With Friends</h2>
    <div class="bottom-photos">
      <img src="received_1543516420336538.jpeg" alt="Ariane with friend 1">
      <img src="received_827796609770433.jpeg" alt="Ariane with friend 2">
      <img src="received_812719168166728.jpeg" alt="Ariane with friend 3">
    </div>

    <h2>My Hobbies</h2>
    <div class="skills">
      <span>Playing Badminton</span>
      <span>Eating</span>
      <span>Watching TikTok</span>
    </div>

    <h2>Contact</h2>
    <div class="contact">
      <p>Email: <a href="mailto:arianeellano64@gmail.com">arianeellano64@gmail.com</a></p>
      <p>Phone: <a href="tel:09925490028">09925490028</a></p>
      <p>Facebook: <a href="https://facebook.com" target="_blank">Visit Profile</a></p>
      <p>Instagram: <a href="https://instagram.com" target="_blank">@bbyariane</a></p>
    </div>

    <footer>
      <p>&copy; Ariane Ellano — All rights reserved</p>
    </footer>
  </div>
</body>
</html>