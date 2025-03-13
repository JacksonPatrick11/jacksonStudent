---
layout: base
title: Student Home
description: Home Page
hide: true
---

<!-- Main container -->
<div style="font-family: 'Segoe UI', Arial, sans-serif; background: linear-gradient(to bottom, #ffffff, #f0f0f0); padding: 20px; min-height: 100vh;">
  
  <!-- Header -->
  <div style="text-align: center; margin-bottom: 40px;">
    <h1 style="font-family: 'Poppins', sans-serif; font-size: 3em; color: #1a237e;">Jackson's Learning Portfolio</h1>
    <p style="font-size: 1.2em; color: #424242;">A collection of my Computer Science journey and projects</p>
  </div>

  <!-- Main Content Grid -->
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; margin: 0 auto; max-width: 1200px;">
    
    <!-- Course Work Section -->
    <div style="background: white; border-radius: 15px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); padding: 25px;">
      <h2 style="text-align: center; color: #1a237e; border-bottom: 2px solid #e0e0e0; padding-bottom: 10px;">📚 Course Work</h2>
      <ul style="list-style: none; padding: 0;">
        <li style="margin: 10px 0;"><a href="./mcblog.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">📝 Multiple Choice Review</a></li>
        <li style="margin: 10px 0;"><a href="sprint2.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">🏃 Sprint 2 Work</a></li>
        <li style="margin: 10px 0;"><a href="CSblog.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">💻 CS Blog</a></li>
        <li style="margin: 10px 0;"><a href="final2.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">📝 Final Blog Tri 2</a></li>
      </ul>
    </div>

    <!-- Notebooks Section -->
    <div style="background: white; border-radius: 15px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); padding: 25px;">
      <h2 style="text-align: center; color: #1a237e; border-bottom: 2px solid #e0e0e0; padding-bottom: 10px;">📓 Jupyter Notebooks</h2>
      <ul style="list-style: none; padding: 0;">
        <li style="margin: 10px 0;"><a href="notebook1.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">📘 Notebook 1 - Python Basics</a></li>
        <li style="margin: 10px 0;"><a href="notebook2.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">📗 Notebook 2 - Data Structures</a></li>
        <li style="margin: 10px 0;"><a href="notebook3.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">📙 Notebook 3 - Algorithms</a></li>
        <li style="margin: 10px 0;"><a href="ECblog.html" style="text-decoration: none; color: #2962ff; display: block; padding: 8px; border-radius: 5px; transition: background-color 0.3s;">📕 Notebook 4 - Advanced Topics</a></li>
      </ul>
    </div>

    <!-- Other sections remain unchanged -->

  </div>

  <!-- Mario Animation -->
  <div>
    <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/de21qfq-4e1bfdda-0157-4558-9583-0b0c3ea6fb05.gif" alt="Mario walking" style="position: fixed; bottom: 0; left: 0; width: 100px; height: 100px; animation: walk 15s linear infinite;">
  </div>

  <!-- Comments Section -->
  <div style="margin-top: 50px;">
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
      from { transform: translateX(-100px); }
      to { transform: translateX(calc(100vw + 100px)); }
    }

    button:hover {
      transform: scale(1.05);
      transition: transform 0.2s ease;
    }

    a:hover {
      background-color: #bbdefb !important;
      transition: background-color 0.3s ease;
    }
  </style>
</div>
