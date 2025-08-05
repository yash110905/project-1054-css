
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Yash Patel | Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Playfair+Display:wght@700&display=swap"rel="stylesheet"
  />
  <script
    src="https://kit.fontawesome.com/a076d05399.js"
    crossorigin="anonymous"
    defer
  ></script>
</head>
<body>
  <div class="particles">
    <div></div>
    <div></div>
    <div></div>
  </div>

  <div class="hero">
    <div class="overlay"></div>
    <div class="hero-content">
      <h1>Yash Patel</h1>
      <p>Cybersecurity & Web Development Enthusiast</p>
      <a href="#projects" class="btn">Explore My Work</a>
    </div>
  </div>

  <header class="sticky-nav">
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="about" id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>
        I'm a Computer Programming and Analysis student passionate about
        <strong>cybersecurity</strong>, <strong>web development</strong>, and
        creating cutting-edge solutions. Inspired by clean design and
        interactivity, I build experiences that engage users.
      </p>
    </div>
  </section>

  <section class="projects-section" id="projects">
    <div class="container">
      <h2>Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <img src="C:\Users\ASUS\Downloads\student record.png" alt="Student Records Website" />
          <div class="card-content">
            <h3>Student Records Website</h3>
            <p>Responsive PHP & MySQL project for managing student records with custom UI.</p>
            <a href="#" class="btn small">View Project</a>
          </div>
        </div>
        <div class="project-card">
          <img src="C:\Users\ASUS\Downloads\treasure hunt.png" alt="Treasure Hunt Game" />
          <div class="card-content">
            <h3>Treasure Hunt Game</h3>
            <p>A text-based C# game with randomness, adaptive interactions & level progression.</p>
            <a href="#" class="btn small">View Project</a>
          </div>
        </div>
        <div class="project-card">
          <img src="C:\Users\ASUS\Downloads\networking.png" alt="Networking Labs" />
          <div class="card-content">
            <h3>Networking Lab Configurations</h3>
            <p>Hands-on Cisco configurations, subnetting, and troubleshooting LAN/WAN issues.</p>
            <a href="#" class="btn small">View Project</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="skills-section" id="skills">
    <div class="container">
      <h2>Skills</h2>
      <div class="skills-cloud">
        <span class="skill">C#</span>
        <span class="skill">C++</span>
        <span class="skill">Python</span>
        <span class="skill">HTML & CSS</span>
        <span class="skill">PHP & MySQL</span>
        <span class="skill">Networking</span>
        <span class="skill">Cybersecurity</span>
      </div>
    </div>
  </section>

  <section class="contact-section" id="contact">
    <div class="container">
      <h2>Contact</h2>
      <p>Let's collaborate! Feel free to reach out via email or connect with me on LinkedIn.</p>
      <p>Email: <a href="mailto:pyash4521@gmail.com">pyash4521@gmail.com</a></p>
      <p>LinkedIn: 
        <a href="https://www.linkedin.com/in/yash-patel-098ba8342" target="_blank">
          www.linkedin.com/in/yash-patel-098ba8342
        </a>
      </p>
      <a href="mailto:pyash4521@gmail.com" class="btn small">Send Message</a>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Yash Patel.</p>
    </div>
  </footer>
</body>
</html>
/* Global Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
body {
  background: #f9fafb;
  color: #374151;
  line-height: 1.6;
  scroll-behavior: smooth;
  min-height: 100vh;
  position: relative;
  z-index: 1;
  overflow-x: hidden;
}

/*  Particles Background  */
.particles {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  pointer-events: none;
  z-index: 0;
  overflow: visible;
}
.particles::before,
.particles::after,
.particles div {
  content: '';
  position: absolute;
  border-radius: 50%;
  background: rgba(59, 130, 246, 0.3);
  opacity: 0.8;
  will-change: transform;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
}

/* Speeds increased */
.particles::before {
  width: 200px;
  height: 200px;
  top: 10%;
  left: 15%;
  animation-name: floatParticle1;
  animation-duration: 8s;
}

.particles::after {
  width: 150px;
  height: 150px;
  bottom: 20%;
  right: 10%;
  animation-name: floatParticle2;
  animation-duration: 9s;
}

.particles div:nth-child(1) {
  width: 100px;
  height: 100px;
  top: 30%;
  left: 70%;
  animation-name: floatParticle3;
  animation-duration: 6s;
}

.particles div:nth-child(2) {
  width: 180px;
  height: 180px;
  top: 60%;
  left: 25%;
  animation-name: floatParticle4;
  animation-duration: 10s;
}

.particles div:nth-child(3) {
  width: 130px;
  height: 130px;
  top: 75%;
  left: 80%;
  animation-name: floatParticle5;
  animation-duration: 7s;
}

/* Floating animations */
@keyframes floatParticle1 {
  0%, 100% { transform: translate3d(0, 0, 0); }
  50% { transform: translate3d(25px, -30px, 0); }
}

@keyframes floatParticle2 {
  0%, 100% { transform: translate3d(0, 0, 0); }
  50% { transform: translate3d(-20px, 25px, 0); }
}

@keyframes floatParticle3 {
  0%, 100% { transform: translate3d(0, 0, 0); }
  50% { transform: translate3d(15px, 20px, 0); }
}

@keyframes floatParticle4 {
  0%, 100% { transform: translate3d(0, 0, 0); }
  50% { transform: translate3d(-25px, -15px, 0); }
}

@keyframes floatParticle5 {
  0%, 100% { transform: translate3d(0, 0, 0); }
  50% { transform: translate3d(20px, 10px, 0); }
}

/* Gradient Background Animation */
.hero {
  animation: gradientShift 4s ease-in-out infinite;
  will-change: background-position;
  background: linear-gradient(270deg, #2563eb, #3b82f6, #60a5fa, #93c5fd, #2563eb);
  background-size: 1000% 1000%;
  position: relative;
  z-index: 1;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: #111827;
  padding: 0 1rem;
}
@keyframes gradientShift {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}

/* Links */
a {
  color: #3b82f6;
  text-decoration: none;
  transition: color 0.3s ease;
}
a:hover,
a:focus {
  color: #2563eb;
  outline: none;
}

/* Buttons*/
.btn {
  display: inline-block;
  background: #3b82f6;
  color: white;
  padding: 0.7rem 1.8rem;
  border-radius: 9999px;
  font-weight: 600;
  box-shadow: 0 8px 15px rgba(59, 130, 246, 0.2);
  transition: all 0.35s ease;
  cursor: pointer;
  user-select: none;
}
.btn:hover,
.btn:focus {
  background: #2563eb;
  box-shadow: 0 10px 20px rgba(37, 99, 235, 0.3);
  transform: translateY(-3px);
}
.btn.small {
  padding: 0.35rem 0.9rem;
  font-size: 0.85rem;
  max-width: 120px;   /* limit maximum width */
  width: auto;        /* prevent full width stretching */
  display: inline-block; /* keep natural button size */
}


/* Hero Content */
.hero-content {
  max-width: 800px;
  animation: fadeInUp 1.2s ease forwards;
}
.hero h1 {
  font-family: 'Playfair Display', serif;
  font-weight: 700;
  font-size: 3.5rem;
  margin-bottom: 0.4rem;
  letter-spacing: 1.5px;
}
.hero p {
  font-size: 1.3rem;
  margin-bottom: 1.5rem;
  color: #4b5563;
}

/* Sticky Navigation*/
.sticky-nav {
  position: sticky;
  top: 0;
  background: #ffffffcc;
  backdrop-filter: saturate(180%) blur(10px);
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
  z-index: 100;
}
.sticky-nav ul {
  display: flex;
  justify-content: center;
  gap: 2.5rem;
  list-style: none;
  padding: 1.2rem 0;
}
.sticky-nav a {
  color: #374151;
  font-weight: 600;
  font-size: 1.05rem;
  transition: color 0.3s ease;
}
.sticky-nav a:hover,
.sticky-nav a:focus {
  color: #3b82f6;
  outline: none;
}

/*Container */
.container {
  max-width: 1100px;
  margin: 0 auto;
  padding: 2.5rem 1.5rem;
}

/*Section Titles */
section h2 {
  font-size: 2.2rem;
  font-weight: 700;
  text-align: center;
  margin-bottom: 1.5rem;
  color: #111827;
  position: relative;
}
section h2::after {
  content: '';
  display: block;
  width: 70px;
  height: 3px;
  background: #3b82f6;
  margin: 10px auto 0;
  border-radius: 2px;
}

/*About Section */
.about p {
  max-width: 700px;
  margin: 0 auto;
  text-align: center;
  font-size: 1.125rem;
  color: #4b5563;
  line-height: 1.8;
}

/* Projects Section */
.projects-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}
.project-card {
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 6px 15px rgba(0, 0, 0, 0.07);
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  display: flex;
  flex-direction: column;
}
.project-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  transition: scale 0.3s ease;
}
.project-card:hover img {
  scale: 1.05;
}
.card-content {
  padding: 1.3rem 1.5rem 2rem;
  flex-grow: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.project-card h3 {
  font-weight: 700;
  font-size: 1.4rem;
  margin-bottom: 0.7rem;
  color: #1f2937;
}
.project-card p {
  flex-grow: 1;
  color: #6b7280;
  font-size: 1rem;
  margin-bottom: 1.3rem;
}
.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 25px rgba(59, 130, 246, 0.3);
}

/* Skills Section */
.skills-cloud {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0.8rem;
}
.skill {
  background: #e0e7ff;
  color: #4338ca;
  padding: 0.6rem 1.2rem;
  border-radius: 9999px;
  font-weight: 600;
  font-size: 1rem;
  transition: background-color 0.3s ease, color 0.3s ease, transform 0.3s ease;
  cursor: default;
}
.skill:hover {
  background-color: #c7d2fe;
  color: #3730a3;
  transform: scale(1.1);
}

/*Contact Section */
.contact-section p {
  text-align: center;
  max-width: 600px;
  margin: 0 auto 1rem;
  font-size: 1.125rem;
  color: #4b5563;
}
.contact-section .btn {
  
  margin: 1rem auto 0;
  margin-left: 465px;
  display: inline-block;  /* make sure button doesn't stretch */
  max-width: 180px;
  width: auto;
}


/* Footer*/
footer {
  text-align: center;
  padding: 1.8rem;
  background: #f3f4f6;
  color: #6b7280;
  font-size: 0.95rem;
  user-select: none;
  border-top: 1px solid #e5e7eb;
}

/*Animations*/
@keyframes fadeInUp {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

/*Responsive  */
@media (min-width: 768px) {
  .hero h1 {
    font-size: 4.5rem;
  }
  .projects-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  .project-card img {
    height: 220px;
  }
}
@media (min-width: 1024px) {
  .projects-grid {
    grid-template-columns: repeat(3, 1fr);
  }
  .project-card img {
    height: 200px;
  }
}
