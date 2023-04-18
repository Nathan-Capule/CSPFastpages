---
toc: true
layout: post
description: cpt
categories: [CPT]
title: CPT
---

<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Goals</title>
    <link rel="stylesheet" href="track.css">
  </head>
  <body>
    <main class="table">
      <section class="table_header">
        <h1>Pipes Game</h1>
      </section>
      <section class="table_body">
<html>
<head>
  <title>Clickable Image</title>
</head>
<body>
  <h2>Click on an area of the image to reveal a question and answer prompt</h2>
  <img id="myImage" src="Pipe Game Wireframe.png" alt="Clickable Image" usemap="#image-map">
  <map name="image-map">
    <area shape="rect" coords="50,114,24,80" onclick="showPrompt('bdsals?', 'Pis')">
    <area shape="rect" coords="100,0,200,100" onclick="showPrompt('dsa?', 'Madsa')">
    <area shape="rect" coords="0,100,100,200" onclick="showPrompt('dsataly?', 'Rdsa')">
    <area shape="rect" coords="500,100,600,200" onclick="showPrompt('Wdsaany?', 'Bdsain')">
  </map>

  <script>
    function showPrompt(question, answer) {
      var userAnswer = prompt(question);
      if (userAnswer === answer) {
        alert("Correct!");
      } else {
        alert("Incorrect. The correct answer is " + answer + ".");
      }
    }
  </script>
</body>
</html>