# My HTML Resume Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VOID001 Resume</title>
  <style>
    /* Add your CSS styles here */
    /* For example: */
    body {
      font-family: Arial, sans-serif;
    }
    .stuff {
      margin: 20px;
      padding: 20px;
      border: 1px solid #ccc;
      background-color: #f5f5f5;
      box-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
    }
    .head {
      font-weight: bold;
      margin-bottom: 5px;
    }
    ul {
      list-style-type: disc;
      padding-left: 20px;
    }
    #header, .left, .right, #footer {
      /* Define your positioning and styles here */
      /* For example: */
      width: 25%;
      float: left;
    }
  </style>
</head>
<body>
  <div id="header"></div>
  <div class="left"></div>
  <div class="stuff">
    <br><br>
  
    <h1>Resume</h1>
    <img src="IMG_6548.JPG" alt="Hi there " width="100" height="133">
    <h2>Mangesh .T Phadte</h2>
    <hr />
    <br>
    
    <p class="head">About me</p>
    
      <p> i am an enthusiastic learner in
        pursuit of my dream to be <br> the
        top cyber-security Analyst in
        India
      </p>
    

    <p class="head">Interests</p>
    <ul>
      <li>Cycling</li>
      <li>Photography</li>
      <li>Video-Photo editing</li>
      <li>Reading</li>
      <li>Computer Science</li>
    </ul>
    <p class="head">Skills</p>
    <ul>
      <li>Web Design with HTML & CSS</li>
      <li>Red team cybersecurity </li>
    </ul>
    <p class="head">Education</p>

    <ul>
        <li>Mustifund High School</li>

        <li>Govt higher secondary school,Khandola</li>

      <a href="https://pccegoa.edu.in/">
        <li>Padre Conceição College Of Engineering</li>
      </a>
    </ul>

    <p class="head">Projects</p>
    <ul>
      <li>Aahara meals</li>

      <li>Student Data base management in
        C++ </li>

      <li>Bus reservation management
          system in C++</li>
    </ul>
    <p class="head">Certified courses</p>
    <ul>
      <li>C++ Programming
        </li>
      <li>Android Development
       </li>
      <li> Ethical Hacking and Cybersecurity</li>
    </ul>

  </div>
  <div class="right"></div>
  <div id="footer">
    <h2 id="name">Copyright VOID001 © </h2>
    <h6>All rights reserved 2023 </h6>
  </div>
</body>
</html>


