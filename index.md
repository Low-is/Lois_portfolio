---
layout: home
title: "Lois Randolph Portfolio"
---

<!-- Navigation -->
<nav class="navbar">
  <a href="#about">About Me</a>
  <a href="#experience">Experience</a>
  <a href="#research">Research</a>
  <a href="blog/blog.html" target="_blank">Guides/Projects</a>
  <a href="#publications-presentations">Publications/Presentations</a>
  <a href="#contact">Contact</a>
</nav>

<!-- About Me -->
<section id="about">
<div class="about-me-section">
<h1 class="welcome-header">
Hello and welcome! <i class="fas fa-smile smile-icon"></i>
</h1>

<div class="about-row-container">

<div class="left-container">
  <div class="about-image">
    <div class="image-block">
      <img src="{{ '/assets/images/Me.jpg' | relative_url }}" alt="Photo of Lois">
      <div class="portrait-title">
        <h2>Lois Randolph (she/her)</h2>
      </div>

      <div class="icon-bar">
        <a href="mailto:lois.randolph@outlook.com"><i class="fas fa-envelope big-icon"></i></a>
        <a href="https://www.linkedin.com/in/lois-randolph/" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com/Low-is" target="_blank"><i class="fab fa-github"></i></a>
      </div>

      <div class="fun-facts">
        <h2 class="section-title">About Me</h2>
        <ul>
          <li>Your friendly neighborhood bioinformatician 💻</li>
          <li>Avid Rollerblader 🛼</li>
          <li>Rubix Cube Enthusiast 🤓</li>
          <li>Unapologetically an anime fanatic 🥷</li>
          <li>Probably dancing while you're reading this 💃🏾</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<div class="right-container">
<div class="about-box">
  <div class="about-me">
    <p>Thank you for visiting my portfolio page! My name is Lois Randolph and I was born and raised in San Antonio, Texas. I attended the University of Texas at San Antonio where I received my B.S. in Biology with a minor in Mathematics. I spent a gap year as a PREP (Postbaccalaureate Research Education Program) scholar at the University of Texas Health Science Center San Antonio, successfully finishing the year-long rigorous program that prepared me for graduate school. After completing my post-bac program, I was later accepted into the UT Health SA Graduate School of Biomedical Sciences where I earned my M.S. in Cancer Biology. During my time in graduate school, I served as the Advocacy Chair for UTHSCSA PRIDE and vice president for ALLIES, volunteerin at clinical events that raise awareness to queer youth having access to healthcare, mental health resources, educational development programs, and hosting multiple student-led social events.</p>
    <p>I'm a biologist by training but a programmer at heart, with a deep passion for precision medicine, computational biology, data science, machine learning, AI, and data engineering. I'm primarily self-taught in R, Python, SQL, HTML, CSS and Linux. I enjoy the challenges presented to me that involve, building prediction models to identify biomarkers to improve medical treatments, manage tools & databases used by teams, institutions, and companies for data storage, data processing, and quality control, and developing pipelines that can automate tasks improving work efficiency. Though this is a different career path I was not expecting, I believe that "where there is passion and inspiration, you can't go wrong".</p>
  </div>
</div>

<!-- Education -->
<div class="education-section">
<h2 class="section-title">Education</h2>
<ul>
<li>M.S. in Cancer Biology, May 2023 - University of Texas Health Science Center San Antonio</li>
<li>B.S. in Biology, Minor in Mathematics, May 2020 - University of Texas at San Antonio</li>
</ul>
</div>
</div>

</div>
</section>

<!-- Experience -->
<section id="experience">
<h1>Experience</h1>
<div class="experience-timeline-container">
  <!-- Repeat your timeline items -->
</div>
</section>

<!-- Research -->
<section id="research">
<h1 class="section-title">Research</h1>
<!-- Repeat your project sections -->
</section>

<!-- Contact -->
<section id="contact">
<h1>Contact Me</h1>
<ul>
  <li><a href="mailto:lois.randolph@outlook.com">Personal Email</a></li>
  <li><a href="mailto:randolphl@uthscsa.edu">Work Email</a></li>
  <li><a href="https://www.linkedin.com/in/lois-randolph">LinkedIn</a></li>
</ul>
</section>

<!-- Popup -->
<div class="overlay" id="popup">
  <div class="popup-box">
    <button class="close-btn" onclick="closePopup()">×</button>
    <h2>🚧 Under Construction</h2>
    <p>My site is still a work in progress — but feel free to explore what’s already here!</p>
  </div>
</div>

<script>
window.onload = function() { document.getElementById('popup').style.display = 'flex'; }
function closePopup() { document.getElementById('popup').style.display = 'none'; }
</script>

<p>Hand-coded with <i class="fas fa-heart" style="color:red;"></i> by Lois Randolph.</p>
