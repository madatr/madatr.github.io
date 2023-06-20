<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="header">
    <nav class="nav container">
      <a href="#" class="nav__logo">Your Name</a>
      <div class="nav__menu">
        <ul class="nav__list">
          <li class="nav__item"><a href="#projects" class="nav__link">Projects</a></li>
          <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
        </ul>
      </div>
    </nav>

    <div class="intro">
      <div class="container">
        <h1 class="intro__title">Hi, I'm Your Name</h1>
        <p class="intro__subtitle">I'm a passionate developer</p>
        <a href="#contact" class="btn">Contact Me</a>
      </div>
    </div>
  </header>

  <main>
    <section id="projects" class="section">
      <div class="container">
        <h2 class="section__title">Projects</h2>
        <div class="projects">
          <!-- Add your project cards here -->
          <div class="project">
            <img src="project1.jpg" alt="Project 1" class="project__img">
            <h3 class="project__title">Project 1</h3>
            <p class="project__description">Description of Project 1</p>
          </div>
          <div class="project">
            <img src="project2.jpg" alt="Project 2" class="project__img">
            <h3 class="project__title">Project 2</h3>
            <p class="project__description">Description of Project 2</p>
          </div>
        </div>
      </div>
    </section>
    <section id="contact" class="section">
      <div class="container">
        <h2 class="section__title">Contact</h2>
        <p>Email: yourname@example.com</p>
        <p>Phone: (123) 456-7890</p>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <p>&copy; 2023 Your Name</p>
    </div>
  </footer>
</body>
</html>
