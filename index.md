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











<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        img {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100px;
            height: 100px;
            animation: walk 10s linear infinite;
        }
        @keyframes walk {
            from { transform: translateX(-100%); }
            to { transform: translateX(calc(100vw + 100px)); }
        }
    </style>
</head>
<body>
    <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/i/eb3b5a4f-6de2-4e44-8b57-ea55bc65fc86/dckxbxg-db6c8283-8e87-497b-92bc-f1f2be4a57cf.gif" alt="Mushroom walking"> 
</body>
</html>




