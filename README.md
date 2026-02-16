<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abinaya Vinoth | Software Engineer</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color:#ffffff;
}

/* NAVBAR */
nav{
    position:fixed;
    width:100%;
    padding:15px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:rgba(0,0,0,0.4);
    backdrop-filter: blur(10px);
    z-index:1000;
}

nav h2{
    font-weight:700;
    color:#00f5ff;
}

nav ul{
    list-style:none;
    display:flex;
    gap:25px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    font-size:14px;
    transition:0.3s;
}

nav ul li a:hover{
    color:#00f5ff;
}

/* HERO */
header{
    height:100vh;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:0 8%;
}

.hero-text{
    max-width:600px;
}

.hero-text h1{
    font-size:50px;
    font-weight:700;
}

.hero-text span{
    color:#00f5ff;
}

.hero-text p{
    margin:20px 0;
    font-size:18px;
    color:#e0e0e0;
}

.btn{
    display:inline-block;
    padding:12px 25px;
    margin-right:15px;
    border-radius:30px;
    text-decoration:none;
    font-weight:500;
    transition:0.3s;
}

.primary-btn{
    background:#00f5ff;
    color:#000;
}

.primary-btn:hover{
    background:white;
}

.secondary-btn{
    border:2px solid #00f5ff;
    color:#00f5ff;
}

.secondary-btn:hover{
    background:#00f5ff;
    color:black;
}

.profile-img{
    width:280px;
    border-radius:50%;
    border:6px solid #00f5ff;
    box-shadow:0 0 40px rgba(0,245,255,0.6);
}

/* SECTIONS */
section{
    padding:100px 8%;
}

h2{
    font-size:32px;
    margin-bottom:40px;
    color:#00f5ff;
}

.card{
    background:rgba(255,255,255,0.08);
    backdrop-filter: blur(10px);
    padding:30px;
    border-radius:15px;
    margin-bottom:25px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
    box-shadow:0 10px 30px rgba(0,245,255,0.3);
}

.skills span{
    display:inline-block;
    padding:8px 16px;
    margin:5px;
    border-radius:20px;
    background:rgba(0,245,255,0.2);
    font-size:14px;
}

footer{
    text-align:center;
    padding:30px;
    background:rgba(0,0,0,0.4);
    font-size:14px;
}

/* RESPONSIVE */
@media(max-width:900px){
    header{
        flex-direction:column;
        text-align:center;
    }
    .profile-img{
        margin-top:40px;
    }
}
</style>
</head>

<body>

<nav>
    <h2>Abinaya Vinoth</h2>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<header>
    <div class="hero-text">
        <h1>Hi, I'm <span>Abinaya Vinoth</span></h1>
        <p>
            Final Year ECE Student transitioning into Software Engineering. 
            Passionate about building scalable web applications and intelligent IoT systems.
        </p>

        <a href="Abinaya_CV.pdf" download class="btn primary-btn">Download CV</a>
        <a href="#projects" class="btn secondary-btn">View Projects</a>
    </div>

    <!-- Replace file name with your photo -->
    <img src="yourphoto.jpg" alt="Abinaya Vinoth" class="profile-img">
</header>

<section id="about">
    <h2>About Me</h2>
    <div class="card">
        I am a final-year Electronics and Communication Engineering student with 
        internship experience in Full Stack Development at NSIC, Chennai.
        My focus is 70% software engineering and 30% IoT & embedded systems.
        I enjoy developing real-world solutions using web technologies and hardware integration.
    </div>
</section>

<section id="skills">
    <h2>Technical Skills</h2>
    <div class="card skills">
        <span>Python</span>
        <span>JavaScript</span>
        <span>HTML5</span>
        <span>CSS3</span>
        <span>Git & GitHub</span>
        <span>REST APIs</span>
        <span>ESP32</span>
        <span>IoT Systems</span>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="card">
        <h3>Smart Vehicle Theft Control System</h3>
        <p>IoT-based vehicle security system with real-time monitoring and anomaly detection alerts.</p>
    </div>

    <div class="card">
        <h3>Smart Wearable Assistant for Visually Impaired</h3>
        <p>Assistive wearable device integrating sensors for obstacle detection and mobility enhancement.</p>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <div class="card">
        <p>Email: yourmail@gmail.com</p>
        <p>GitHub: github.com/yourusername</p>
        <p>LinkedIn: linkedin.com/in/yourprofile</p>
    </div>
</section>

<footer>
    © 2026 Abinaya Vinoth | Designed & Developed with Passion
</footer>

</body>
</html>
