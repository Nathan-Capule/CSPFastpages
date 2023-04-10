---
toc: true
layout: post
description: What the title said
categories: [CPT]
title: CPT Writeup
---

## [Video Here](https://drive.google.com/file/d/1Igub2Sq3OX9eFO8xkUcnbgltS78sFgtE/view)

## 3.a:

### 3.a.i: Describes the overall purpose of the program

* The purpose of this program is to allow users to easily track their current workouts and edit the current workout, sets, and reps.

### 3.a.ii: Describes what functionality of the program is demonstrated in the video

* This program allows users to add a new row in a table. Within that row they can add what workout they are completing, how many sets they are completing, and how many reps within each set. There is also a button that allows the user to clear all workouts that they have inputted, allowing item to create a new workout.

### 3.a.iii: Describes the input and output of the program demonstrated in the video

* In the video, the user adds a new workout, that being situps, as well as adds 5 sets and 50 reps. Then the user submits the data and adds a row that contains that data. Finally, the user deletes the data.

## 3.b

### 3.b.i: The first program code segment must show how data have been stored in the list.

![]({{ site.baseurl }}/images/3.b.i.png "3.b.i")

![]({{ site.baseurl }}/images/3.b.ii.png "3.b.i")
 

### 3.b.ii: The second program code segment must show the data in the same list being used, such as creating new data from the existing data or accessing multiple elements in the list, as part of fulfilling the program’s purpose.

![]({{ site.baseurl }}/images/3.b.ii2.png "3.b.ii")

### 3.b.iii: Identifies the name of the list being used in this response

I have a collection method in which the data scored includes the workout, the number of sets, and the number of reps. All of this data is stored within a table called “users”. This data can be deleted through a function that resets all data. 

### 3.b.iv: Describes what the data contained in the list represent in your program

The data that is stored are workouts, sets, and reps. This data can be stored as strings, so the inputs can be either words such as “pushups” for the workout category, or numbers such as “10” for the number of sets.

### 3.b.v: Explains how the selected list manages complexity in your program code by explaining why your program code could not be written, or how it would be written differently, if you did not use the list

The database is able to manage complexity as it is able to take the users inputs, format it into a table, and store the information. Without the database, the inputs by the user would be lost every time they refreshed the page. Without the database, this program would be useless.

## 3.C

### 3.C.i: The first program code segment must be a student-developed procedure that: 
□ Defines the procedure’s name and return type (if necessary) 
□ Contains and uses one or more parameters that have an effect on the functionality of the procedure 
□ Implements an algorithm that includes sequencing, selection, and iteration

### Procedure:
![]({{ site.baseurl }}/images/3.c.i.png "3.c.i")
### Call:
![]({{ site.baseurl }}/images/call1.png "call")
![]({{ site.baseurl }}/images/call2.png "call")
![]({{ site.baseurl }}/images/call3.png "call")
![]({{ site.baseurl }}/images/call4.png "call")

### 3.c.ii: The second program code segment must show where your student-developed procedure is being called in your program.

![]({{ site.baseurl }}/images/3.c.ii.png "3.c.ii")
![]({{ site.baseurl }}/images/3.c.iii.png "3.c.ii")

There are two functions here, a create function and a read function.

The create function will create a new row in the. From the user's inputs, it will add a workout, the number of reps, and the number of sets. This will then be stored in the database to be retrieved later.

### 3.c.iii: Describes in general what the identified procedure does and how it contributes to the overall functionality of the program

The read function is what will display the data. After fetching the data from the database, the read function will then be able to display the data in the frontend in a neat manner, this allows for the user to see the stored data. This means that we do not need a create function to see the data, we just need to have the data already in the database and have a read function to display it.

### 3.c.iv: Explains in detailed steps how the algorithm implemented in the identified procedure works. Your explanation must be detailed enough for someone else to recreate it.

Sequence: I used sequencing in my code by adding a create function. First, it will get all the data from the user's inputs, and then it will display them in the table below. This is a sequence as the code goes in sequential order.

Selection: I had a selection within my code through the submit button. This button would only take data that was within the textbox, so there were two options. Either the data would be entered, or it would display an error message and have the user fill out all boxes.

Iteration: I had a function that would keep trying to display the inputted information until all data is printed. I completed this using a for loop in which for each piece of data, the function will input the data until all data has been added.


## 3.d.

### 3.d.i: First Call

My first call can be seen when you click submit, it calls the data into the backend to be stored. This data is then turned into json data which can be grabbed later. The backend fetches the data from the frontend (the users inputs). 

My second call is when you add the row, it will fetch the data from the backend, which stores all the data. This JSON data is then changed back into data that can be presented neatly within the table.

### 3.d.ii: Describes what condition(s) is being tested by each call to the procedure

The first call just tests to make sure that there is actually data present before being sent to the database. My second call tests to make sure that there is actually data to be outputted into the table.

### 3.d.iii: Identifies the result of each call

The result of the first call is sending data to the database, we can see that from the first call that when data is added, the database is populated with information. The result of the second call is printing the data that the user inputted into a table below the input boxes.

