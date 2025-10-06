<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Clickable Card - AH Toggle</title>
  <style>
    .card {
      width: 300px;
      height: 200px;
      background: linear-gradient(135deg, #1f2a33, #2e3e46);
      position: relative;
      display: grid;
      place-content: center;
      border-radius: 12px;
      overflow: hidden;
      transition: all 0.4s ease-in-out;
      cursor: pointer;
      box-shadow: 0 8px 15px rgba(189, 159, 103, 0.4);
      outline: none;
    }

    .border {
      position: absolute;
      inset: 0;
      border: 2px solid #d4af37;
      opacity: 0.75;
      transform: rotate(10deg);
      transition: all 0.4s ease-in-out;
      box-shadow: 0 0 8px #d4af37;
    }

    .card:hover .border,
    .card:focus .border {
      inset: 10px;
      opacity: 1;
      transform: rotate(0);
      box-shadow: 0 0 15px #ffde7a;
    }

    .text-display {
      color: #d4af37;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-weight: 700;
      text-align: center;
      width: 90%;
      line-height: 1.3;
      user-select: none;
      text-shadow: 0 0 6px #ffde7a;
      transition: font-size 0.3s ease, letter-spacing 0.3s ease;
    }

    .text-small {
      font-size: 56px;
      letter-spacing: 10px;
    }

    .text-large {
      font-size: 16px;
      letter-spacing: 2.5px;
      word-break: break-word;
    }
  </style>
</head>
<body>
  <div class="card" id="toggleCard" aria-pressed="false" role="button" tabindex="0" title="Click to toggle text">
    <div class="border"></div>
    <div class="content">
      <div class="text-display text-small" id="textDisplay">AH</div>
    </div>
  </div>

  <script>
    const card = document.getElementById('toggleCard');
    const textDisplay = document.getElementById('textDisplay');

    const shortText = "AH";
    const fullText = "AYISHATHUL HAZEENA a tech and management enthusiast";

    card.addEventListener('click', () => {
      if (card.getAttribute('aria-pressed') === 'false') {
        textDisplay.textContent = fullText;
        textDisplay.classList.remove('text-small');
        textDisplay.classList.add('text-large');
        card.setAttribute('aria-pressed', 'true');
      } else {
        textDisplay.textContent = shortText;
        textDisplay.classList.remove('text-large');
        textDisplay.classList.add('text-small');
        card.setAttribute('aria-pressed', 'false');
      }
    });

    card.addEventListener('keydown', (e) => {
      if (e.key === 'Enter' || e.key === ' ') {
        e.preventDefault();
        card.click();
      }
    });
  </script>
</body>
</html>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=36DEFF&center=true&vCenter=true&width=800&lines=Tech+%26+Management+Student;Full-Stack+Enthusiast;Building+with+Passion;Always+Learning+New+Things" alt="Typing Roles Animation" />
</p>

<p align="center" style="font-style:italic; color:#4B4B4B;">
  "When passion meets purpose, effort becomes excellence – I strive to give my best when I truly care."
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tech%20%26%20Management%20Student-36DEFF?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Full%20Stack%20Enthusiast-36DEFF?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Building%20with%20Passion-36DEFF?style=for-the-badge&logo=code&logoColor=white" />
</p>

# 💫 About Me:
I love building things that make life easier, spark curiosity, and connect people.<br>Whether it's crafting a website, solving a tricky algorithm, or organizing a team project, I'm always up for a challenge!


## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=plastic&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hazeena-shahul-hameed-b01838292/) 
[![Email](https://img.shields.io/badge/Email-D14836?style=plastic&logo=gmail&logoColor=white)](mailto:tohazsha@gmail.com)  

## 💡 Technical Skills

### Programming Languages
<p align="left">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

### Frontend
<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
</p>

### Backend & Database
<p align="left">
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

### DSA & Problem Solving
<p align="left">
  <img src="https://img.shields.io/badge/Data_Structures-000000?style=for-the-badge&logo=leetcode&logoColor=yellow"/>
  <img src="https://img.shields.io/badge/Problem_Solving-1F8ACB?style=for-the-badge&logo=codechef&logoColor=white"/>
</p>

### Tools & Platforms
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"/>
</p>

## 🌐 Coding platforms

<a href="https://github.com/HazSha28"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" /></a>
<a href="https://codolio.com/profile/Hazeena%20S"><img src="https://img.shields.io/badge/Codolio-1a1a1a?style=flat" /></a>
<a href="https://leetcode.com/u/HAZEENA/"><img src="https://img.shields.io/badge/LeetCode-FFA116?logo=leetcode&logoColor=black&style=flat" /></a>
<a href="https://www.codechef.com/users/kit27csbs11"><img src="https://img.shields.io/badge/CodeChef-5B4638?logo=codechef&logoColor=white&style=flat" /></a>
<a href="https://www.geeksforgeeks.org/user/tohazzwgh/"><img src="https://img.shields.io/badge/GeeksforGeeks-0F9D58?logo=geeksforgeeks&logoColor=white&style=flat" /></a>

## 🌟 Featured Projects

<div align="center" style="max-width: 650px; margin: auto; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #2a2a2a; background: #f9faff; padding: 20px; border-radius: 15px; box-shadow: 0 8px 20px rgba(54, 110, 255, 0.2);"> <h3 style="color: #366aff; margin-bottom: 0.3rem;"> <a href="https://hazsha28.github.io/Flavour-Fusion/" style="color: #254eda; text-decoration: none; font-weight: 700;">Flavour Fusion</a> </h3> <p style="font-size: 16px; max-width: 520px; margin: auto; color: #444;"> Immerse yourself in a world of flavors. This project allows you to <strong style="color:#1e40af;">explore, create, and share recipes</strong> featuring <strong style="color:#1e40af;">step-by-step video tutorials</strong> and interactive cooking guides. </p> <hr style="margin: 2rem 0; border: none; height: 2px; background: linear-gradient(to right, #366aff, #254eda);" /> <h3 style="color: #366aff; margin-bottom: 0.3rem;"> <a href="https://hazsha28.github.io/Todo-App/" style="color: #254eda; text-decoration: none; font-weight: 700;">Todo App</a> </h3> <p style="font-size: 16px; max-width: 520px; margin: auto; color: #444;"> Stay organized with ease by managing your daily tasks efficiently. This app offers <strong style="color:#1e40af;">smooth animations</strong>, <strong style="color:#1e40af;">drag-and-drop functionality</strong>, and <strong style="color:#1e40af;">instant feedback</strong> to enhance productivity. </p> <hr style="margin: 2rem 0; border: none; height: 2px; background: linear-gradient(to right, #366aff, #254eda);" /> <h3 style="color: #366aff; margin-bottom: 0.3rem;"> <a href="https://hazsha28.github.io/Expense-Tracker/" style="color: #254eda; text-decoration: none; font-weight: 700;">Expense Tracker</a> </h3> <p style="font-size: 16px; max-width: 520px; margin: auto; color: #444;"> Visualize and manage your finances effectively. This tool helps you <strong style="color:#1e40af;">track, analyze, and control your expenses</strong> with clarity. </p> <hr style="margin: 2rem 0; border: none; height: 2px; background: linear-gradient(to right, #366aff, #254eda);" /> <h3 style="color: #366aff; margin-bottom: 0.3rem;"> <a href="https://hadith-master.vercel.app/" style="color: #254eda; text-decoration: none; font-weight: 700;">Hadith Master</a> </h3> <p style="font-size: 16px; max-width: 520px; margin: auto; color: #444;"> Enhance your knowledge with ease. This application enables you to <strong style="color:#1e40af;">search, filter, and read Islamic texts</strong>, offering <strong style="color:#1e40af;">AI-powered suggestions, live previews</strong>, and interactive learning tools. </p> </div>

## 🏆 Highlights

<ul style="max-width: 600px; margin: auto; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #2a2a2a; font-size: 16px; line-height: 1.6;">
  <li><strong>Full Stack Development Intern</strong> at <em>Learnlogicify Technologies</em> — Gained hands-on experience in building end-to-end web applications using modern stacks.</li>
  <li><strong>Infosys Certified</strong> in <em>Java Programming</em> — Demonstrated strong proficiency and understanding of Java concepts and applications.</li>
  <li><strong>NPTEL Certified</strong> in <em>Problem Solving with C, DBMS, and Computer Networks</em> — Acquired comprehensive knowledge in key computer science domains.</li>
  <li><strong>2700 / 3000</strong> in <em>CodeChef C Test</em> (90% Skill Score) — Showcasing advanced problem-solving skills and algorithm mastery.</li>
  <li><strong>Regular participant</strong> in global programming contests on <em>CodeChef</em> — Continuously improving competitive programming skills through challenges.</li>
</ul>

# 📊 GitHub Stats:

![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=HazSha28&theme=codeSTACKr)
![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=HazSha28&theme=codeSTACKr)
![](http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=HazSha28&theme=codeSTACKr)

## 🏆 GitHub Trophies
<p align="center">
 [ ![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=Hazsha28&theme=vue&no-frame=true&no-bg=true&margin-w=4)](https://github-profile-trophy.vercel.app/?username=HazSha28&theme=juicyfresh)
</p>

## 🎯 Hobbies & Interests

<p><div style="max-width: 600px; margin: auto; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: #2a2a2a; font-size: 16px; line-height: 1.6;">
  <p><strong>Exploring emerging technologies:</strong> Staying updated with the latest trends and tools in software development.</p>
  <p><strong>Public Speaking:</strong> Actively participating in clubs like Toastmasters to hone communication and leadership skills.</p>
  <p><strong>Creative Design:</strong> Designing graphics, fonts, and UI elements as a creative outlet and to enhance user experiences.</p>
  <p><strong>Puzzles and Problem Solving:</strong> Enjoying brain teasers, coding contests, and algorithm challenges to sharpen logical thinking.</p>
  <p><strong>Travel and Culture:</strong> Experiencing new places and cultures to broaden perspectives and fuel inspiration.</p>
</div>
</p>
<p align="center">
  <b>Fun Fact</b><br>
  <i>"Striving to merge innovation with impact, one project at a time!"</i>
  <br><br>
  ⭐ From <a href="https://github.com/HazSha28">HazSha28</a>
</p>
