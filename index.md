---
layout: base
title: Student Home 
description: Home Page
hide: true
---


<!-- title page saying welcome to jackosns page -->
<center>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        @keyframes colorChange {
            0% { color: red; }
            25% { color: orange; }
            50% { color: purple; }
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

<!-- button and links -->
<div class="wrapper-outline">
    <div class="container">
        <p>This is a paragraph</p>
        <button onclick="alert('This is a button!')">button</button>
        <div class="top-float-div">div</div>
    </div>

    <div class="container">
        <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank">a</a>
        <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank">a</a>
        <div>div</div>
        <p>This is a paragraph</p>
    </div>
</div>

<style>
.wrapper-outline {
    margin: 5px;
    padding: 5px;
    background-color: white;
}

.container {
    width: 500px;
    margin: 20px auto;
    background-color: white;
    padding: 20px;
    border: 2px solid black;
}

.top-float-div {
    position: absolute;
    left: 49%;
    top: 30%;
    color: black !important;
    text-align: center;
}

.container p {
    border: 2px solid red;
    color: red !important;
    padding: 5px;
    margin: 10px 0;
}

.container button {
    border: 2px solid lime;
    background-color: white !important;
    color: lime !important;
    padding: 5px 15px;
    margin: 10px 0;
    cursor: pointer;
}

.container button:hover {
    background-color: lime !important;
    color: white !important;
}

.container a {
    display: block;
    border: 2px solid blue;
    color: blue !important;
    text-decoration: none;
    padding: 5px;
    margin: 10px 0;
    text-align: center;
}

.container a:hover {
    background-color: blue !important;
    color: white !important;
}
</style>

<!-- mario runing code -->

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




