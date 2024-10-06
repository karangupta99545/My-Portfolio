# My-Portfolio
<!-- HTML CODE -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>My Portfolio</title>
  </head>
  <body>
    <header>
      <h1>Karan Gupta</h1>
      <p>Web Developer (frontend)</p>
    </header>

    <section id="about">
      <img  src="https://images.pexels.com/photos/1308881/pexels-photo-1308881.jpeg?cs=srgb&dl=pexels-soldiervip-1308881.jpg&fm=jpg"  alt="Karan Gupta">
    </section>

    <section id="about1">
      <h2>
        I'm a passionate web developer and designer with a keen eye for detail.
      </h2>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="project">
        <img src="file:///C:/Users/karan%20gupta/Desktop/photp1.pdf" alt="Project 1" />
        <h3>Project 1</h3>
        <p>Designed and coded a responsive website for a local business.</p>
      </div>
      <div class="project">
        <img src="project2.jpg" alt="Project 2" />
        <h3>Project 2</h3>
        <p>
          Developed a JavaScript-based interactive portfolio showcasing my work.
        </p>
      </div>
    </section>
    <section id="resume">
      <h2>Resume</h2>
      <p><a href="resume.pdf" download> Download Resume (PDF)</a></p>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <p>Email: karangupta99545@gmail.com</p>
      <p>Phone: 9682934643</p>
    </section>
    <footer>
      <p>&copy; Karan Gupta. All rights reserved.</p>
    </footer>
  </body>
</html>

<!-- CSS CODE -->
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: rgb(232, 174, 200);
    padding: 0;
  }
  
  header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
  }
  
  header h1 {
    margin: 0;
  }
  
  #about1 {
    text-align: center;
    padding: 1px 0;
  }
  #about {
    text-align: center;
    padding: 20px 0;
  }
  
  #about img {
    width: 90px;
    border-radius: 30%;
  }
  
  #skills {
    text-align: left;
    padding: 10px 0;
  }
  
  #skills ul {
    list-style: none;
  }
  
  #projects {
    text-align: center;
    padding: 20px 0;
  }
  
  .project {
    margin-bottom: 20px;
  }
  
  .project img {
    max-width: 100%;
    border-radius: 5px;
  }
  
  #resume,
  #contact {
    text-align: center;
    padding: 20px 0;
  }
  
  #resume a {
    text-decoration: none;
    color: #333;
    border: 1px solid #333;
    padding: 10px 20px;
    border-radius: 5px;
  }
  
  footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
  }
  
