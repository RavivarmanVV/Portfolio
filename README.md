# Ex01 Portfolio
## Date: 30.10.2026
## Name: Ravivarman VV
## RegNO: 212224240133

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.
### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Portfolio Website</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#c0b58c;
    color:rgb(0, 0, 0);
}

/* Navbar */
nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 10%;
    background:#3f2c14a7;
    position:sticky;
    top:0;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#00000096;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:25px;
}

nav ul li a{
    text-decoration:none;
    color:rgb(0, 0, 0);
    transition:0.3s;
}

nav ul li a:hover{
    color:#462c0c96;
}

/* Hero Section */
.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:80px 10%;
    flex-wrap:wrap;
}

.hero-text{
    max-width:500px;
    flex: 1;
}

.hero-text h1{
    font-size:50px;
}

.hero-text span{
    color:#462c0c96;
}

.hero-text p{
    margin-top:20px;
    line-height:1.6;
    color:#000000;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:12px 28px;
    background:#462c0c96;
    color:#000;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
    transition:0.3s;
}

.btn:hover{
    background:rgb(190, 7, 7);
}

.hero img{
    width:320px;
    height:400px;
    object-fit:cover;
    border-radius:20px;
    box-shadow:0 0 25px #462c0c96;
    margin-left:40px;
}

/* About */
.about{
    padding:70px 10%;
    text-align:center;
}

.about h2{
    font-size:40px;
    margin-bottom:20px;
    color:#462c0c96;
}

.about p{
    color:#000000;
    line-height:1.8;
}

/* Skills */
.skills{
    padding:70px 10%;
}

.skills h2{
    text-align:center;
    color:#462c0c96;
    margin-bottom:40px;
    font-size:40px;
}

.skill-box{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
}

.skill{
    background:#462c0c96;
    padding:25px;
    width:200px;
    text-align:center;
    border-radius:15px;
    transition:0.3s;
}

.skill:hover{
    transform:translateY(-10px);
    background:#462c0c96;
    color:white;
}

/* Projects */
.projects{
    padding:70px 10%;
}

.projects h2{
    text-align:center;
    font-size:40px;
    color:#462c0c96;
    margin-bottom:40px;
}

.project-container{
    display:flex;
    flex-wrap:wrap;
    gap:20px;
    justify-content:center;
}

.project{
    width:300px;
    background:#462c0c96;
    border-radius:15px;
    overflow:hidden;
    transition:0.3s;
}

.project:hover{
    transform:scale(1.05);
}

.project img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.project-content{
    padding:20px;
}

/* Contact */
.contact{
    padding:70px 10%;
    text-align:center;
}

.contact h2{
    font-size:40px;
    color:#462c0c96;
    margin-bottom:20px;
}

.contact p{
    margin:10px 0;
}

/* Footer */
footer{
    text-align:center;
    padding:20px;
    background:#000;
    margin-top:40px;
    color:#aaa;
}

@media(max-width:768px){
    .hero{
        flex-direction:column;
        text-align:center;
    }

    .hero img{
        margin-top:40px;
    }
}
</style>
</head>

<body>

<!-- Navbar -->
<nav>
    <div class="logo">Portfolio</div>

    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Skills</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>

<!-- Hero Section -->
<section class="hero">

    <div class="hero-text">
        <h1>Hello, I'm <span>RAVIVARMAN VAIDHYAR VAITHYALINGAM</span></h1>

        <p>
            Front-End Developer | Web Designer | Student  
            Passionate learner trying to create beautiful and responsive websites.
        </p>

        <a href="#" class="btn">Hire Me</a>
    </div>

    <!-- Profile Image -->
    
    <img src="0IMG_7517_.jpg" alt="Profile Image">

</section>

<!-- About -->
<section class="about">

    <h2>About Me</h2>

    <p>
        I am a creative web developer with skills in HTML, CSS, JavaScript, 
        and responsive design. I love building modern websites with clean UI.
    </p>

</section>

<!-- Skills -->
<section class="skills">

    <h2>My Skills</h2>

    <div class="skill-box">

        <div class="skill">
            <h3>HTML</h3>
            <p>Advanced Website Structure</p>
        </div>

        <div class="skill">
            <h3>CSS</h3>
            <p>Modern Responsive Design</p>
        </div>

        <div class="skill">
            <h3>JavaScript</h3>
            <p>Interactive Websites</p>
        </div>

        <div class="skill">
            <h3>UI Design</h3>
            <p>Creative Layout Designs</p>
        </div>

    </div>

</section>

<!-- Projects -->
<section class="projects">

    <h2>Projects</h2>

    <div class="project-container">

        <div class="project">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?q=80&w=1000&auto=format&fit=crop">

            <div class="project-content">
                <h3>Portfolio Website</h3>
                <p>Modern personal portfolio using HTML & CSS.</p>
            </div>
        </div>

        <div class="project">
            <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?q=80&w=1000&auto=format&fit=crop">

            <div class="project-content">
                <h3>E-Commerce Site</h3>
                <p>Responsive shopping website with animations.</p>
            </div>
        </div>

        <div class="project">
            <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?q=80&w=1000&auto=format&fit=crop">

            <div class="project-content">
                <h3>Blog Website</h3>
                <p>Clean and attractive blogging platform.</p>
            </div>
        </div>

    </div>

</section>

<!-- Contact -->
<section class="contact">

    <h2>Contact Me</h2>

    <p>Email: ravirepublic16@gmail.com</p>
    <p>Phone: +91 6383681498</p>
    <p>Location: Chennai, India</p>

</section>

<!-- Footer -->
<footer>
    © 2026 RV Portfolio | All Rights Reserved
</footer>

</body>
</html>

## OUTPUT
<img width="1535" height="877" alt="image" src="https://github.com/user-attachments/assets/a0416903-308f-4291-8fe9-e362584b261b" />
<img width="1535" height="877" alt="image" src="https://github.com/user-attachments/assets/c8e13121-9ce7-4045-a27f-218a7a23d577" />
<img width="1535" height="877" alt="image" src="https://github.com/user-attachments/assets/e769e2be-e839-4217-a250-28c7007947f9" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
