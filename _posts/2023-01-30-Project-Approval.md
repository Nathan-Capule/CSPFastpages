---
toc: true
layout: post
description: Here I will show how my part of the project meets all 6 of collegeboards requirements.
categories: [Project Approval]
title: Project Approval
---

# My Feature: Workout Planner

![]({{ site.baseurl }}/images/Tracker.png "Workout Tracker")

## What my feature does
My feature allows people to track their workout while doing it. They can add what muscles they are working on, their workout, their sets, and even their reps. This will allow people to better keep track of their workouts which would lead to increased productivity and better workout sessions.

## Future Goals
There are two main things that I still want to add, I want to add a rest timer, as well as integrate this into the workout calender made by Steven. This will allow users to see what workouts they have completed on other days.

# Collegeboard

## Row 1 - Program Purpose and Function
My video will include me choosing what workout I wil be completing, which is the input. Then it will show how the program works, by moving on to the next category which is selecting the sets and reps for the workout, and finally, here will be an outputted bar that states the sets, reps, and what workout is being completed. The overall purpose of this will be to allow people to log their workout in an easy to manage fashion. My written response will also include how the input and the output are displayed in the video.

## Row 2 - Data Abstraction
The inputs of the user, which are what workout they are completing including their sets and reps, will be stored in a database that will be transferred into a line that is returned which displays those workouts. I will identify the name of the variable that is representing the list through the written response, and I will describe where the data is being contained and how it is later grabbed.

## Row 3 - Managing Complexity
Giving each variable for each workout a name, it will help to make the code easier to manage. I will also be reusing the "reps", "sets", and "cooldowns" for each workout which will help to lessen the length of my code.

## Row 4 - Procedural Abstraction
I have created a procedure that will store the data of a workout and call it back to be displayed within the workout log. This will contribute to the program as it allows me to easily transfer data, this will also make the program look better on the frontend.

## Row 5 - Algorithm Implementation
I will use sequencing through giving instructions on what should be displayed depending on the users input. I will use selection by having the program see what workouts people have added and using it as a new workout. For example, if you do leg presses more than other workouts, it will display as a quick selection option. I will use iterations by having the program log the workout and displaying it.

## Row 6 - Testing
The first call that I will display is calling the reps, sets, and weights after an exercise is chosen. The second one is that if the workout was already chosen, it will display: "Workout has already been chosen, would you like to add this still?".

