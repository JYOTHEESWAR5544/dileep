<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
   
</head>
<body>

    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f3f3f7;
    
}

/* Header */
header {
    top: 0;
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
    position: sticky;
    
}
#Profile{
    background-color: rgb(236, 231, 214);
    text-align: center;
    padding: 20px;
    margin-top: 80px;
}
img{    
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-top: 20px;
}


/* Sections */
section {

    padding: 20px;
    margin: 10px;
    background: rgb(208, 211, 211);
    border-radius: 8px;
}

/* Skills */
.skills ul {
    list-style-type: square;
}

/* Projects */
.project-card {
    background: #f6f7f8;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
}

/* Footer */
footer {
    text-align: center;
    background: #333;
    color: white;
    padding: 10px;
}
#about{
    background-color: rgb(233, 232, 228);
    
}
#contact{
    background-color: rgb(235, 234, 229);
 
}
#CERTIFICATIONS{
    background-color: rgb(226, 226, 222);
    
}
#projects{
    background-color: rgb(231, 231, 227);
    
}
#Atchivements{
    background-color: rgb(226, 226, 221);
    
}
#skills{
    background-color: rgb(233, 232, 228);
    
    
}


#skills{
   
    text-align: center;
} 
.grid-container {

  grid-template-columns: repeat(5, 1fr);
  gap: 10px;
}
.grid-items {
    display: inline;
  background-color: #e3e3e3;
  padding: 10px;
  border-radius: 5px;
  text-align: center;
  border: 1px solid #f0e4e4;
  
}

.links {
    display: flex;
    justify-content: center;
    gap: 50px;
   color: white;
    list-style-type: none;

}
a:hover{
    color: rgb(105, 37, 233);
}



    </style>

    <!-- Header -->
    <header>
        <h1>Dileep Naidu</h1>
        <p>Web Developer</p>
        <nav class="links">
        
            <a href="#about" class="links">About</a>
            <a href="#skills" class="links">Skills</a>
            <a href="#projects" class="links">Projects</a>
            <a href="#CERTIFICATIONS" class="links">Certifications</a>
            <a href="#Atchivements" class="links">Achievements</a>
            <a href="#contact" class="links">Contact</a>
        
    </nav>
    </header>

    <div id="profile">
    <h1>Hello,I'm Dileep naidu Full Stack MERN Developer</h1>
    <p>I build modren websites and applications for businesses.</p>
    <img src="WhatsApp Image 2026-03-19 at 4.00.59 PM.jpeg" alt="Dileep Naidu">
    </div>

    <section class="about">
        <h2 id="about">About Me</h2>
        <p>I’m a passionate web development student with skills in HTML, CSS, JavaScript, Node.js, and MongoDB. I am currently learning full-stack development and working on building real-world projects to improve my skills. I enjoy creating user-friendly and responsive websites that provide a good user experience. I also have knowledge in HR and marketing, which helps me better understand user needs and business goals. I am a quick learner, highly motivated, and eager to grow as a full-stack developer.                </p>
    </section>

    <!-- Skills -->
     <div class="grid-container">
        <div class="grid-items">

    
    <section class="skills">
        <div class="project-card">
        <h2 id="skills">My Skills</h2>
        <ul>
            <li class="grid-items">HTML</li>
            <li class="grid-items">CSS</li>
            <li class="grid-items">JavaScript</li>
            <li class="grid-items">Bootstrap</li>
            <li class="grid-items">React</li>
            <li class="grid-items">Node.js</li>
            <li class="grid-items">MongoDB</li>
            <li class="grid-items">Express.js</li>
            <li class="grid-items">IDE Tools - VS Code</li>

        </ul>
        </div>
    </section>
    </div>
    </div>

    <!-- Projects -->
    <section class="projects">
        <h2 id="projects">My Projects</h2>
        <div class="project-card">
        <h3><u>Flipkart Clone</u></h3>
         <p>The website is a sample website to use the tools are HTML, CSS, and JavaScript.</p>
         <h3><u>PhonePe Bootstrap</u></h3>
            <p>This is a simple Bootstrap project for PhonePe.</p>
            
            
        
            <h3><u>Calculator</u></h3>
            <p>Basic calculator using JavaScript.</p>
            <h3><u>Portfolio Website</u></h3>
            <p>Personal Portfolio with animations.</p>
            <h3><u>Html Document</u></h3>
            <p>Building HTML document for Students.</p>
        
    </section>

    <section class="CERTIFICATIONS">
        <h2 id="CERTIFICATIONS">Certifications</h2>
        <div class="project-card">
            <ul>
                <li>Responsive Web Design – FreeCodeCamp </li>
                    <li>Full Stack Web Developer Certification – Scinex / APSCHE Registered</li>
                
            </ul>
        </div>
    </section>
    <section class="Atchivements">
        <h2 id="Atchivements">Achievements</h2>
        <div class="project-card">
            <ul>
                <li>I made advertisement to take the new brand and own concept to made and got the first price</li>
            <li>I got the second price in the event of "Best Coordinator" in my college</li>
        
            </ul>
        </div>
    </section>

    <!-- Contact -->
    <section class="contact">
        <h2 id="contact">Contact Me</h2>
        <p>Email: dileepnaidu7850@gmail.com</p>
        <p>Phone: +91 7815853709</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Dileep Naidu</p>
    </footer>

</body>
</html>
    
</body>
</html>
