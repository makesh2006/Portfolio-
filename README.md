# Portfolio-

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Makesh kumar - Software Designer</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700&display=swap">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #111;
      color: #f9f9f9;
      text-align: center;
      padding: 2rem 0;
    }
    .header-content {
      max-width: 1200px;
      margin: auto;
      padding: 0 20px;
    }
    .header-content h1 {
      font-size: 2rem;
      margin-bottom: 10px;
    }
    .profile-picture {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin: 20px auto;
    }
    nav {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
    }
    nav ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
    }
    nav ul li {
      display: inline-block;
      margin: 0 20px;
    }
    nav ul li a {
      text-decoration: none;
      color: #fff;
    }
    .section-content {
      background-color: #fff;
      padding: 2rem;
      margin: 2rem auto;
      max-width: 800px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .download-button {
      background-color: #333;
      color: #fff;
      padding: 0.5rem 1rem;
      text-decoration: none;
      border-radius: 20px;
      display: inline-block;
      margin-top: 10px;
    }
    .download-button:hover {
      background-color: #555;
    }
    footer {
      text-align: center;
      padding: 1rem 0;
      background-color: #333;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <div class="header-content">
      <img src="Mk.jpg" alt="Your Profile Picture" class="profile-picture">
      <h1>Makesh kumar D</h1>
      <p>Software Developer</p>
    </div>
  </header>
  <nav>
    <ul>
      <li><a href="#Career Objective">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#resume">Resume</a></li>
    </ul>
  </nav>
  <section id="Career Objective">
    <div class="section-content">
      <h2>Career Objective</h2>
      <p>To secure a challenging position in a reputable organization to expand my learnings, knowledge, and skills. Seeking a challenging position in a reputed organization where I can learn new skills, expand my knowledge, and leverage my learnings.</p>
    </div>
  </section>
  <section id="education">
    <div class="section-content">
      <h2>Education</h2>
      <p>BSC COMPUTER SCIENCE - KAAMADHANU ARTS AND SCIENCE COLLEGE</p>
    </div>
  </section>
  <section id="skills">
    <div class="section-content">
      <h2>Tech Skills</h2>
      <ul>
        <li>Python</li>
        <li>C</li>
        <li>Java</li>
        <li>C++</li>
        <li>JavaScript</li>
      </ul>
    </div>
  </section>
    <section id="skills">
    <div class="section-content">
      <h2>Soft Skills</h2>
      <ul>
        <li>Public Relations</li>
        <li>Teamwork</li>
        <li>Time Management</li>
        <li>Leadership</li>
      </ul>
    </div>
    
    
  <section id="projects">
    <div class="section-content">
      <h2>Projects</h2>
      <ul>
        <li><a href="weather server.html">Weather Report</a></li>
        <li><a href="#">Cloud Security IBM</a></li>
        <li><a href="#">Ai Chatbot</a></li>
        <li><a href="Contact.html">Contact Request</a>
          </section>
          <section id="resume">

    

        <div class="section-content">
            <center>
            <h2>Resume</h2>
            <a href="file.pdf" target="_blank" class="download-button">Download CV</a>
        </center>
        </div>
        
    </section>

    <footer>
        <p>&copy; 2025 </p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^=""]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
