---
layout: base
title: Student Home
description: Home Page
hide: true
---

<!-- Main container -->
<div style="font-family: Arial, sans-serif; background: linear-gradient(to bottom, #f7f7f7, #eaeaea); padding: 20px; min-height: 100vh;">
  
  <!-- Header -->
  <div style="text-align: center; margin-bottom: 40px;">
    <h1 style="font-family: 'Pacifico', cursive; font-size: 3em; color: #2c3e50;">Welcome to Jackson's Page</h1>
    <p style="font-size: 1.2em; color: #34495e;">Explore resources, games, and more!</p>
  </div>

  <!-- Categories Section -->
  <div style="display: flex; justify-content: space-evenly; flex-wrap: wrap; gap: 20px; margin-bottom: 40px;">
    
  <!-- Educational Section -->
  <div style="flex: 1; min-width: 300px; background: #ecf0f1; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); padding: 20px;">
      <h2 style="text-align: center; color: #2c3e50;">Educational Resources</h2>
      <ul style="list-style: none; padding: 0; text-align: center;">
        <li><a href="./mcblog.html" style="text-decoration: none; font-size: 1.1em; color: #2980b9;">Multiple Choice Blog and Review</a></li>
        <li><a href="sprint2.html" style="text-decoration: none; font-size: 1.1em; color: #2980b9;">Sprint 2</a></li>
        <li><a href="notebook1.html" style="text-decoration: none; font-size: 1.1em; color: #2980b9;">Notebook 1</a></li>
        <li><a href="notebook2.html" style="text-decoration: none; font-size: 1.1em; color: #2980b9;">Notebook 2</a></li>
        <li><a href="notebook3.html" style="text-decoration: none; font-size: 1.1em; color: #2980b9;">Notebook 3</a></li>
        <li><a href="ECblog.html" style="text-decoration: none; font-size: 1.1em; color: #2980b9;">Notebook 4</a></li>
        <li><a href="CSblog.html" style="text-decoration: none; font-size: 1.1em; color: #2980b9;">CS Blog</a></li>
      </ul>
    </div>

  <!-- Gaming Section -->
  <div style="flex: 1; min-width: 300px; background: #ecf0f1; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); padding: 20px;">
      <h2 style="text-align: center; color: #2c3e50;">Gaming Zone</h2>
      <div style="text-align: center;">
        <button onclick="window.location.href='navigation/cookieclicker.html'" style="background-color: #3498db; color: white; padding: 10px 20px; margin: 5px; border-radius: 5px; border: none; font-size: 1em; cursor: pointer;">Cookie Clicker</button>
        <button onclick="window.location.href='navigation/Binarycalculator.html'" style="background-color: #e74c3c; color: white; padding: 10px 20px; margin: 5px; border-radius: 5px; border: none; font-size: 1em; cursor: pointer;">Binary Calculator</button>
        <button onclick="window.location.href='navigation/snakegame.html'" style="background-color: #1abc9c; color: white; padding: 10px 20px; margin: 5px; border-radius: 5px; border: none; font-size: 1em; cursor: pointer;">Snake Game</button>
      </div>
    </div>
  </div>

  <!-- Mario Animation -->
  <div>
    <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/de21qfq-4e1bfdda-0157-4558-9583-0b0c3ea6fb05.gif" alt="Mario walking" style="position: fixed; bottom: 0; left: 0; width: 120px; height: 120px; animation: walk 10s linear infinite;">
  </div>

  <!-- Additional Features Section -->
  <div style="text-align: center; margin-bottom: 40px;">
    <p style="font-size: 1.2em; color: #34495e;">Additional Features</p>
    <table style="margin: 0 auto; border-collapse: collapse; font-size: 1.1em; text-align: center;">
      <tr>
        <td style="padding: 10px;"><a href="{{site.baseurl}}/pythonnotebook/" style="color: #2980b9;">Challenges</a></td>
        <td style="padding: 10px;"><a href="{{site.baseurl}}/javascript/" style="color: #2980b9;">Python</a></td>
        <td style="padding: 10px;"><a href="{{site.baseurl}}/thingy/" style="color: #2980b9;">JS</a></td>
      </tr>
    </table>
  </div>

  <!-- Utterances Comments Section -->
  <div>
    <script src="https://utteranc.es/client.js"
            repo="Mom5MoreMins/aranya_student_2025"
            issue-term="pathname"
            theme="github-dark"
            crossorigin="anonymous"
            async>
    </script>
  </div>

  <!-- Custom CSS -->
  <style>
    @keyframes walk {
      from { transform: translateX(-100%); }
      to { transform: translateX(100vw); }
    }

    button:hover {
      transform: scale(1.1);
      transition: transform 0.3s ease;
    }

    table td a {
      text-decoration: none;
    }
  </style>
</div>
