<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rajesh Kumar | AI Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>
body {
    margin:0;
    font-family:'Poppins', sans-serif;
    color:white;
    background: linear-gradient(135deg,#020617,#0f172a,#1e293b);
}

/* NAVBAR */
nav {
    display:flex;
    justify-content:space-between;
    padding:20px;
}
nav h1 {color:#38bdf8;}
nav a {color:white; margin:0 10px; text-decoration:none;}

/* HERO */
.hero {
    text-align:center;
    padding:100px 20px;
}
.hero h1 {
    font-family:'Orbitron';
    font-size:45px;
    color:#38bdf8;
}

/* IMAGE */
.avatar {
    width:170px;
    height:170px;
    border-radius:50%;
    object-fit:cover;
    object-position: top center;
    border:3px solid #38bdf8;
    box-shadow:0 0 30px #38bdf8;
    margin-top:20px;
}

/* SECTION */
.section {
    max-width:900px;
    margin:auto;
    padding:50px 20px;
}

/* CARD */
.card {
    background: rgba(255,255,255,0.08);
    backdrop-filter: blur(10px);
    padding:20px;
    border-radius:15px;
    margin:15px 0;
    transition:0.3s;
}
.card:hover {
    transform: translateY(-10px);
    box-shadow:0 0 30px #38bdf8;
}

/* BUTTON */
.btn {
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:#38bdf8;
    color:black;
    border-radius:10px;
    text-decoration:none;
}

/* SKILLS */
.skills span {
    display:inline-block;
    background:linear-gradient(45deg,#38bdf8,#a78bfa);
    color:black;
    padding:10px 15px;
    margin:5px;
    border-radius:20px;
    transition:0.3s;
}
.skills span:hover {
    transform: scale(1.1);
    box-shadow:0 0 15px #38bdf8;
}
.skills h3 {
    color:#38bdf8;
    margin-top:20px;
}

/* FOOTER */
footer {
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<nav>
<h1>RAJESH</h1>
<div>
<a href="#about">About</a>
<a href="#projects">Projects</a>
<a href="#experience">Experience</a>
<a href="#skills">Skills</a>
</div>
</nav>

<section class="hero">
<h1>AI Developer Portfolio</h1>
<p>Python | Machine Learning | Data Analysis</p>

<img src="images/profile.jpg" class="avatar">

<br>
<a href="resume/resume.pdf" class="btn" download>Download Resume</a>
</section>

<section id="about" class="section">
<div class="card">
<h2>About Me</h2>
<p>B.Tech AI student skilled in Python, Machine Learning, NLP, and data analysis. Passionate about building intelligent systems.</p>
</div>
</section>

<section id="projects" class="section">
<div class="card">
<h2>Projects</h2>
<p><b>AI Sentiment Analysis System:</b> NLP-based sentiment classification.</p>
<p><b>Student Performance Prediction:</b> ML model to predict academic performance.</p>
</div>
</section>

<section id="experience" class="section">
<div class="card">
<h2>Experience</h2>

<h3>AI & Machine Learning Intern (AICTE)</h3>
<p>Worked on AI concepts and ML techniques during internship training.</p>

<h3>Summer Internship – IIIT Hyderabad</h3>
<p>Learned real-world machine learning applications and implementations.</p>

</div>
</section>

<section id="skills" class="section">
<div class="card">
<h2>Skills</h2>

<div class="skills">

<h3>Technical Skills</h3>
<span>Python</span>
<span>SAP ABAP</span>
<span>Machine Learning</span>
<span>NLP Basics</span>
<span>Web Development</span>
<span>MySQL</span>
<span>Git & GitHub</span>
<span>MS Excel</span>
<span>MS Word</span>

<h3>Soft Skills</h3>
<span>Hardworking</span>
<span>Time Management</span>
<span>Team Work</span>
<span>Communication</span>

</div>

</div>
</section>

<footer>
<p>© 2026 Rajesh Kumar</p>
</footer>

</body>
</html>
