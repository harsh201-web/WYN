# WYN
website 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WYN Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #222;
    }
    header {
      background-color: #1a1a1a;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 50px 20px;
      text-align: center;
    }
    h1 {
      color: #007acc;
    }
    p {
      font-size: 1.2rem;
    }
    footer {
      background-color: #1a1a1a;
      color: white;
      padding: 15px;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    .button {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #007acc;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .button:hover {
      background-color: #005fa3;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to WYN</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About WYN</h2>
      <p>WYN is a simple, clean, and fun website created using GitHub Pages. You can edit this page to share whatever you want: blogs, projects, or your favorite things!</p>
      <a class="button" href="#contact">Get in Touch</a>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Want to say hi? Send us an email at <a href="mailto:wyn@example.com">wyn@example.com</a>.</p>
    </section>
  </main>

  <footer>
    &copy; 2026 WYN. All rights reserved.
  </footer>

</body>
</html>
