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
    background: rgb(44, 44, 150);
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2rem;
    text-decoration: underline 2px;
    text-underline-offset: 10px;
  }
  
  .calculator {
    width: 80%;
    max-width: 400px;
    margin: 20px auto;
    padding: 20px;
    background: linear-gradient(180deg, #ffffff, #f2f2f2);
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    -webkit-box-shadow: 0 0 4px black;
     box-shadow: 0 0 4px black;
  }
  
  .calculator input {
    width: 100%;
    margin-bottom: 10px;
    padding: 10px;
    font-size: 20px;
    text-align: right;
    border: none;
    border-radius: 4px;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1);
  }
  
  .calculator button {
    width: 70px;
    height: 70px;
    margin: 5px;
    font-size: 24px;
    background-color: #e5e5e5;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  .calculator button:hover {
    background-color: #d4d4d4;
  }
  
  .calculator button:active {
    background-color: #bbbbbb;
  }
  
  .buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
  }
  
  @media (max-width: 480px) {
    .calculator {
      width: 100%;
    }
    
    .calculator input {
      font-size: 18rem;
    }
    
    .calculator button {
      width: 60rem;
      height: 60rem;
      font-size: 16rem;
    }
}
