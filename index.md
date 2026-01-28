---
layout: home
title: "Lois Randolph Portfolio"
---

<!-- Font Awesome -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">

<!-- Custom CSS -->
<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

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
      <!-- Left Column -->
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

      <!-- Right Column -->
      <div class="right-container">
        <div class="about-box">
          <div class="about-me">
            <p>Thank you for visiting my portfolio page! My name is Lois Randolph and I was born and raised in San Antonio, Texas. I attended the University of Texas at San Antonio where I received my B.S. in Biology with a minor in Mathematics. I spent a gap year as a PREP scholar at the University of Texas Health Science Center San Antonio, successfully completing the rigorous year-long program preparing me for graduate school. I then earned my M.S. in Cancer Biology from UT Health SA Graduate School of Biomedical Sciences. During grad school, I served as Advocacy Chair for UTHSCSA PRIDE and VP for ALLIES, volunteering at clinical events for queer youth access to healthcare and education, and hosting student-led social events.</p>

            <p>I'm a biologist by training but a programmer at heart, passionate about precision medicine, computational biology, data science, ML, AI, and data engineering. I'm primarily self-taught in R, Python, SQL, HTML, CSS, and Linux. I enjoy building predictive models, managing tools/databases, and automating pipelines to improve efficiency.</p>
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
  </div>
</section>

<!-- Experience -->
<section id="experience">
  <h1>Experience</h1>
  <div class="experience-timeline-container">
    <div class="timeline">
      <div class="timeline-item">
        <div class="timeline-marker filled"></div>
        <div class="timeline-content">
          <h3>Bioinformatician</h3>
          <p><strong>Dec. 2023 - Present</strong><br>Department of Neonatology | University of Texas Health Science Center San Antonio</p>
        </div>
      </div>
      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <h3>Graduate Research Assistant</h3>
          <p><strong>Aug. 2021 – May 2023</strong><br>Dept. of Obstetrics & Gynecology | UT Health SA</p>
        </div>
      </div>
      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <h3>Intern</h3>
          <p><strong>June 2021 – Aug. 2021</strong><br>Human Genome Sequencing Center | Baylor College of Medicine</p>
        </div>
      </div>
      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <h3>PREP Scholar</h3>
          <p><strong>June 2020 - June 2021</strong><br>Biochemical Mechanisms in Medicine | UT Health SA</p>
        </div>
      </div>
      <div class="timeline-item">
        <div class="timeline-marker"></div>
        <div class="timeline-content">
          <h3>RISE Scholar | Research Assistant</h3>
          <p><strong>Dec. 2018 - May 2020</strong><br>Neuroscience, Developmental & Regenerative Biology | UT San Antonio</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Research -->
<section id="research">
  <h1 class="section-title">Research</h1>

  <!-- Repeat project block -->
  <div class="project project-light">
    <h2>Meta-analysis of DNA Methylation Profiles in Infants with BPD</h2>
    <p>Infants born <30 weeks PMA are at risk for long-term complications. This study conducted a meta-analysis of independent neonatal DNA methylation datasets to identify robust markers linked to BPD development.</p>
    <p><strong>Citation:</strong> Manuscript in progress</p>
    <p><strong>R packages used:</strong> GEOquery, readxl, dplyr, tidyr, pdftools, stringr, ChAMP, minfi, wateRmelon, parallel, meta, ggrepel, qqman, recipes, themis, caret, pROC, ROCR, rcompanion, ggplot2, CMplot, pbapply</p>
  </div>

  <!-- Repeat similar blocks for each project... -->
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
