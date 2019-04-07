+++
date = "2019-04-07"
title = "CPSC 581 - Assignment 3"
math = "true"

+++

## Beer Hat Wearable

#### Context

In this project, we were tasked to solve an everyday problem by utilizing a combination of hardware and software, and develop a physical prototype demonstrating our proof of concept for a piece of wearable technology. After a long process of exploring different ideas and many discussions, we finally landed on one idea as our favorite candidate, a beer hat wearable.

<hr>

#### Sketch Design Phase

- These were the initial sketches at the beginning stage of our ideation process when I was brainstorming ideas for interesting fashion technology. Some of my ideas were derived from everyday problems I experienced. For instance, one particular idea that stood out was creating an all season jacket that contains a built-in heating mechanism that adjusts according to the weather or your selected heating preferences.

- Moreover, another idea that stood out as useful but intrusive at the same time was a hat that would automatically spray you with sunscreen. The idea behind this sunscreen hat was that during the summer season, many of us forget to put on sunscreen and end up red as a tomato after a long day from sunburns.

<div class="row1">
  <div class="column1">
    <img onClick="location.href='https://i.imgur.com/7DuZchz.jpg';" src="https://i.imgur.com/7DuZchz.jpg" alt="Initial Sketches" style="width:100%">
  </div>
  <div class="column1">
    <img onClick="location.href='https://i.imgur.com/Ota3rbI.jpg';" src="https://i.imgur.com/Ota3rbI.jpg" alt="Initial Sketches" style="width:100%">
  </div>
</div>

<center><b>Initial Sketches</b></center>

<style>
    /* Three image containers (use 25% for four, and 50% for two, etc) */
.column1 {
  float: left;
  width: 50%;
  padding: 5px;
}

/* Clear floats after image containers */
.row1::after {
  content: "";
  clear: both;
  display: table;
}

img:hover {
    cursor: pointer;
}
</style>

- After the many rounds of feedback we have received in class from our peers, and team discussions narrowing down our top candidate, we decided to proceed with the idea of a beer hat wearable that would let servers know when you have run out of beer and need a refill.

- [**Album Link**](https://imgur.com/a/JHGOMpM)

<div class="row2">
  <div class="column2">
    <img onClick="location.href='https://i.imgur.com/1elI7Yp.jpg';" src="https://i.imgur.com/1elI7Yp.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column2">
    <img onClick="location.href='https://i.imgur.com/9VdGetE.jpg';" src="https://i.imgur.com/9VdGetE.jpg" alt="Forest" style="width:100%">
  </div>
  <div class="column2">
    <img onClick="location.href='https://i.imgur.com/79SVpkI.jpg';" src="https://i.imgur.com/79SVpkI.jpg" alt="Mountains" style="width:100%">
  </div>
</div>

<center><b>Beer Hat Sketches</b></center>

<style>
    /* Three image containers (use 25% for four, and 50% for two, etc) */
.column2 {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row2::after {
  content: "";
  clear: both;
  display: table;
}

img:hover {
    cursor: pointer;
}
</style>

#### Implementation

- In this implementation phase, we utilized an old Raspberry Pi to write, compile, and test our code. As shown in the video demonstration, once the user has drank all the beer and the sensor detects that it is no longer full, the hat would light up to let a server known that you need a refill.

<center>
    **YouTube Video**
</center>

<center><b>Video Demonstration</b></center>



<hr>
<hr>

#### Source Code

- Download the source code from [GitHub](https://github.com/muhannadnouri/CPSC_581-Assgn3)

#### Contributors

- Alexander Lam
- Joseph Gorospe
- Michael Verwaayen
- Mitchell Rudy
- Muhannad Nouri