# PORTFOLIO

Header Section: Add your name or a logo at the top. Optionally, include a brief introduction or tagline.

About Section: Insert an image of yourself. Write a short bio highlighting your skills and experience.

Skills Section: List your key skills or areas of expertise.

Projects Section: Showcase samples of your work or projects. Include project titles, descriptions, and images.

Contact Section: Include your contact information, such as email address and phone number.

Footer: Add a copyright notice and any additional links or information.

## PORT.HTML:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="port.css" />
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <section id="home">
      <img
        style="border-radius: 150px"
        src="C:\Users\sujith20112015\Desktop\INTERN\portfolio\images\image.jpg"
        ,
        alt="image not found"
        ,width="200px"
        height="100px"
      />
      <h1>Welcome to My Portfolio</h1>
      <p>Hello! I am NITEESH M, a Front-End Developer.</p>
    </section>

    <section id="about">
      <h2>About Me</h2>
      <h3>Hi all I'm NITEESH👋</h3>
      <p>
        I'm a Artificial Intelligence and Data Science student with a keen
        interest in becoming a web developer. Proficient in Python, C, HTML, and
        CSS, with some knowledge of JavaScript. I possess substantial expertise
        in the field of data science and am currently engaged in an internship
        focused on data science at Elysian Intelligence Business
        Solution (EIBS).
      </p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>HTML/CSS</li>
        <li>JAVASCRIPT</li>
        <li>Python</li>
        <li>MySQL</li>
        <li>GIT/GITHUB</li>
        <li>DATA SCIENCE</li>
        <li>MACHINE LEARNING</li>
        <li>ARTIFICIAL INTELLIGENCE</li>
      </ul>
    </section>

    <section id="projects">
      <h2>My Projects</h2>
      <div class="project">
        <h3>Project 1</h3>
        <h5>Project Title: Development of a Company's Landing Page</h5>
        <p style="font-weight: bold">Objective:</p>
        <p>
          To design and develop a responsive and user-friendly landing page
          optimized for lead generation and enhanced user experience using
          data-driven insights.
        </p>
        <p style="font-weight: bold">Project Overview:</p>
        <p>
          The landing page project involved creating a dynamic web interface
          aimed at capturing user interest and converting visitors into
          potential leads. The project utilized web development technologies and
          data analytics to ensure the landing page was visually appealing,
          functional, and effective in achieving business objectives.
        </p>
        <h3>Skills Demonstrated:</h3>
        <ul>
          <li>Web development and Frond-End design</li>
          <li>Data analysis</li>
          <li>User experience design</li>
          <li>Analytical thinking and problem-solving.</li>
        </ul>
        <p style="font-weight: bold">Github link:</p>
        <p>
          <a href="https://github.com/Niteeshmohan/landingpage.git"
            >https://github.com/Niteeshmohan/landingpage.git</a
          >
        </p>

        <center>
          <img
            src="C:\Users\sujith20112015\Desktop\INTERN\portfolio\images\L1.png"
            ,
            height="200px"
            ,width="100px"
          />
        </center>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <h5>
          Project Title: Development of a Standard calculator using HTML and CSS
        </h5>
        <p style="font-weight: bold">Objective:</p>
        <p>
          To design and develop a responsive standard calculator to implement
          functions for addition, subtraction, multiplication and division.
        </p>
        <p style="font-weight: bold">Project Overview:</p>
        <p>
          Developed a fully functional standard calculator application designed
          to perform basic arithmetic operations including addition,
          subtraction, multiplication, and division. This project aimed to
          create a user-friendly interface that mimics the functionality of a
          physical calculator, ensuring accurate and efficient calculations.
          Developed a real-time display to show the current input and ongoing
          calculations, enhancing usability.
        </p>
        <h3>Technologies Used:</h3>
        <ul>
          <li>Programming Language: [Python/Java/C++/JavaScript, etc.]</li>
          <li>Development Tools: [Visual Studio Code]</li>
          <li>
            Version Control: Utilized Git for version control to manage project
            development and collaboration.
          </li>
        </ul>
        <p style="font-weight: bold">Github link:</p>
        <p>
          <a href="https://github.com/Niteeshmohan/CALCULATOR.git"
            >https://github.com/Niteeshmohan/CALCULATOR.git</a
          >
        </p>
        <center>
          <img
            src="C:\Users\sujith20112015\Desktop\INTERN\portfolio\images\CALC.png"
            ,
            height="200px"
            ,width="100px"
          />
        </center>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>Phone: 86819 09463</p>
      <p>
        <a href="https://www.linkedin.com/in/niteesh-mohan-59b417288/"
          >LinkedIn: niteesh-mohan</a
        >
      </p>
      <p>
        <a href="https://github.com/Niteeshmohan">GitHub: Niteeshmohan</a>
      </p>
      <p>
        <a
          href="https://mail.google.com/mail/u/0/#inbox
        "
          >Email: warriorniteesh11@gmail.com
        </a>
      </p>
      <p>
        <a href="https://github.com/Niteeshmohan">GitHub: Niteeshmohan</a>
      </p>
      <br />
    </section>

    <footer>
      <p>&copy; 2024 Niteeshmohan. All rights reserved.</p>
    </footer>
  </body>
</html>

```

## PORT.CSS:

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
}

#home {
    background: #f4f4f4;
    text-align: center;
    padding: 50px 20px;

}

#projects .project {
    background: #e2e2e2;
    margin: 10px 0;
    padding: 10px;
}
#contact-form {
    display: flex;
    flex-direction: column;
    width: 300px;
    margin: 0 auto;
}

#contact-form label {
    margin-top: 10px;
}

#contact-form input, #contact-form textarea {
    padding: 10px;
    margin-top: 5px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}


```

## PORT.JS:

```
document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Thank you for your message!');
});


```

## OUTPUT:

![Screenshot 2024-07-11 213048](https://github.com/Niteeshmohan/PORTFOLIO/assets/119575445/8911a906-d5e2-4183-9dd4-3b54ea3e5884)

![Screenshot 2024-07-11 213056](https://github.com/Niteeshmohan/PORTFOLIO/assets/119575445/76473a89-08b4-4f52-b4bd-e0d6c1d1fa32)

![Screenshot 2024-07-11 213107](https://github.com/Niteeshmohan/PORTFOLIO/assets/119575445/fcc04283-4461-420d-9262-54caebc7105b)


![Screenshot 2024-07-11 213115](https://github.com/Niteeshmohan/PORTFOLIO/assets/119575445/a07b02cf-e15c-48f2-be47-cdbb525df1fc)



