---
toc: true
layout: post
description: What the title said
categories: [CPT]
title: Collegeboard Big Idea Quiz 2 Corrections
---

## My Score + Reflection
![]({{ site.baseurl }}/images/bigidea2score.png "Overall Score")

I got a 24/25 which I am actually pretty proud of. Overall I have seen an upward trend in the score that I have. But there are still many things that I can do to help guarantee a perfect score when I take the AP test.

## Question 17:

I only missed one question on the test, that question was number 17.

![]({{ site.baseurl }}/images/Q171.png "Question Number")

### Here is the question and my answer:

![]({{ site.baseurl }}/images/Q172.png "The answer in question")

This question was a skill from 5.B asking about what could be extracted with the information given. I chose C which stated "The most expensive item purchased on a given date can be determined by searching the data for all items purchased on the given date and then sorting the matching items by item price". I chose option C because I thought that you 














### 3.a.i:

* The purpose of this program is to allow users to easily track their current workouts and edit the current workout, sets, and reps.

### 3.a.ii:

* This program allows users to add a new row in a table. Within that row they can add what workout they are completing, how many sets they are completing, and how many reps within each set. There is also a button that allows the user to clear all workouts that they have inputted, allowing item to create a new workout.

### 3.a.iii:

* There are 3 inputs for the user to add: workout, reps, and sets. After that, they click submit to send it to the database. They can also press add row to add a workout without sending it to the database, allowing them to test workout sets without having to delete anything. Finally, there is a delete function where all the data within the database is cleared..

## 3.b

### 3.b.i:

![]({{ site.baseurl }}/images/bigidea2score.png "3.b.i")

![]({{ site.baseurl }}/images/3.b.ii.png "3.b.i")
 

### 3.b.ii

![]({{ site.baseurl }}/images/3.b.ii2.png "3.b.ii")

I have a collection method in which the data scored includes the workout, the number of sets, and the number of reps. All of this data is stored within a table called “users”. This data can be deleted through a function that resets all data. I am working on adding an update function that would allow users to edit workouts, this is just a personal project though as I was not able to figure out how to complete it within the timeframe of this assignment.

### 3.b.iv.

The data that is stored are workouts, sets, and reps. This data can be stored as strings, so teh inputs can be either words such as “pushups” for the workout category, or numbers such as “10” for the number of sets.

### 3.b.v.

The database is able to manage complexity as it is able to take the users inputs, format it into a table, and store the information. Without the database, the inputs by the user would be lost every time they refreshed the page. Without the database, this program would be useless.

## 3.C

### 3.C.i
### Procedure:
![]({{ site.baseurl }}/images/3.c.i.png "3.c.i")
### Call:
![]({{ site.baseurl }}/images/call1.png "call")
![]({{ site.baseurl }}/images/call2.png "call")
![]({{ site.baseurl }}/images/call3.png "call")
![]({{ site.baseurl }}/images/call4.png "call")

### 3.c.ii

![]({{ site.baseurl }}/images/3.c.ii.png "3.c.ii")
![]({{ site.baseurl }}/images/3.c.iii.png "3.c.ii")

There are two functions here, a create function and a read function.

The create function will create a new row in the. From the user's inputs, it will add a workout, the number of reps, and the number of sets. This will then be stored in the database to be retrieved later.

The read function is what will display the data. After fetching the data from the database, the read function will then be able to display the data in the frontend in a neat manner, this allows for the user to see the stored data. This means that we do not need a create function to see the data, we just need to have the data already in the database and have a read function to display it.

### 3.c.iv.

Sequence: I used sequencing in my code by adding a create function. First, it will get all the data from the user's inputs, and then it will display them in the table below. This is a sequence as the code goes in sequential order.

Selection: I had a selection within my code through the submit button. This button would only take data that was within the textbox, so there were two options. Either the data would be entered, or it would display an error message and have the user fill out all boxes.

Iteration: I had a function that would keep trying to display the inputted information until all data is printed. I completed this using a for loop in which for each piece of data, the function will input the data until all data has been added.


## 3.d.

### 3.d.i

My first call can be seen when you click submit, it calls the data into the backend to be stored. This data is then turned into json data which can be grabbed later. The backend fetches the data from the frontend (the users inputs). 

My second call is when you add the row, it will fetch the data from the backend, which stores all the data. This JSON data is then changed back into data that can be presented neatly within the table.

### 3.d.ii.

The first call just tests to make sure that there is actually data present before being sent to the database. My second call tests to make sure that there is actually data to be outputted into the table.

### 3.d.iii

The result of the first call is sending data to the database, we can see that from the first call that when data is added, the database is populated with information. The result of the second call is printing the data that the user inputted into a table below the input boxes.

## What I learned/Struggles

This was actually very difficult for me, I struggled to create a fulls tack. After getting help from multiple people, I was finally able to understand how to create a full stack and how I can use this in the future. It was a very good learning experience for me just not as a student but also as a person. There is more than one way to solve a problem and it is okay to get help from others. That is probably a lesson that I learned in this class that no other class has ever tried to teach me.
