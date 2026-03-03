<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Rinante Orwa | Portfolio</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: Arial, sans-serif;
}

body {
background: #f4f6f9;
color: #333;
line-height: 1.6;
}

header {
background: #1e3a8a;
color: white;
padding: 20px 0;
text-align: center;
}

nav {
margin-top: 10px;
}

nav a {
color: white;
text-decoration: none;
margin: 0 15px;
font-weight: bold;
}

nav a:hover {
text-decoration: underline;
}

section {
padding: 60px 20px;
max-width: 1000px;
margin: auto;
}

.about img {
width: 150px;
border-radius: 50%;
display: block;
margin: 20px auto;
}

.projects {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 20px;
}

.card {
background: white;
padding: 20px;
border-radius: 10px;
box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.card img {
width: 100%;
border-radius: 8px;
}

.contact a {
display: inline-block;
margin: 10px;
color: #1e3a8a;
text-decoration: none;
font-weight: bold;
}

footer {
background: #1e3a8a;
color: white;
text-align: center;
padding: 20px;
}

.btn {
display: inline-block;
padding: 10px 20px;
background: #2563eb;
color: white;
border-radius: 5px;
text-decoration: none;
margin-top: 10px;
}

.btn:hover {
background: #1e40af;
}
</style>
</head>

<body>

<header>
<img src="profile.jpg" alt="My Profile Picture">
<h1>Rinante Orwa</h1>
<p>Student | Lifelong Learner | maintenance</p>
<nav>
<a href="#about">About</a>
<a href="#projects">Projects</a>
<a href="#blog">Blog</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section id="about" class="about">
<h2>About Me</h2>
<img src="profile.jpg" alt="Profile Picture">
<p>
Hello! I am Rinante Orwa, a passionate student who loves learning new things,
playing pickleball is my sports and i really love it
</p>
</section>

<section id="projects">
<h2>My Projects</h2>
<div class="projects">


<div class="card">
<img src="project1.jpg" alt="Project 1">
<h3>School Blog</h3>
<p>A blog website where I share reflections and lessons.</p>
<a href="#" class="btn">View Project</a>
</div>

</div>
</section>

<section id="blog">
<h2>Blog</h2>
<p>
I write about technology, student life, and personal growth.
Stay tuned for updates!
</p>
</section>

<section id="contact" class="contact">
<h2>Contact Me</h2>
<p>Email: orwarinante1@gmail.com</p>
<a href="#">Facebook</a>
<a href="#">GitHub</a>
<a href="#">LinkedIn</a>
</section>

<footer>
<p>© 2026 Rinante Orwa | All Rights Reserved</p>
</footer>

</body>
</html>
