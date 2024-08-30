---
layout: base
title: Student Home 
description: Home Page
hide: true
---



<center>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        @keyframes colorChange {
            0% { color: red; }
            25% { color: orange; }
            50% { color: yellow; }
            75% { color: green; }
            100% { color: blue; }
        }

        .color-fade {
            font-size: 5em; /* font size */
            font-weight: bold;
            animation: colorChange 5s infinite; /* _s =seconds cycle, infinite loop */
        }
    </style>
</head>
<body>

    <p class="color-fade">Welcome to Jackson's page</p>

</body>
</html>


</center>








<div>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden; /* Prevents scrollbars */
        }

        .dog-container {
            position: fixed;
            bottom: 0;
            width: 100%;
            display: flex;
            justify-content: flex-start; /* Start from the left */
            align-items: center;
            animation: moveRight 5s linear infinite alternate; /* Move back and forth */
        }

        .dog {
            display: flex;
            align-items: center;
            font-family: Arial, sans-serif;
            font-size: 2em;
            font-weight: bold;
        }

        .dog img {
            width: 50px; /* Adjust size as needed */
            height: auto;
            margin-right: 10px;
        }

        @keyframes moveRight {
            from {
                transform: translateX(0);
            }
            to {
                transform: translateX(calc(100vw - 60px)); /* Moves across the screen */
            }
        }
    </style>
</head>
<body>
    <div class="dog-container">
        <div class="dog">
            <img src="https://media2.giphy.com/media/SqeYW7O2ppikWbffph/giphy.gif?cid=6c09b952s9pei7plyvmsa75oddtadg63yomxzp9dgx88b5ej&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=s" alt="Dog">
            <span>Welcome</span>
        </div>
    </div>
</body>
</html>


</div>