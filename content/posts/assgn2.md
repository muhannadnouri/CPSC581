+++
date = "2019-03-17"
title = "CPSC 581 - Assignment 2"
math = "true"

+++

## Colour Sorting Machine

#### Context

In this project, we were tasked to solve an everyday problem by utilizing a combination of hardware and software, and develop a physical prototype demonstrating our proof of concept. We were given an Arduino computer and had access to any choice of sensors we desired. Through a long process of exploring many different ideas, we finally landed on one idea as our top candidate, a colour sorting machine for candy.

<hr>

#### Sketch Design Phase

- These were the initial sketches of when I was brainstorming ideas for a machine that solves an everyday problem. When I was searching for ideas, I tried to look into the mundane everyday things we do that we can automate or avoid doing altogether.

- Some of my ideas involved the use of smart lights such as the smart light bulb that would reduce blue light levels after sunset.

- Another idea involving the use of lighting was a machine that would illuminate your staircase and any other desired sections of your house during the night. The rationale behind that idea was to avoid altogether a situation where you cannot see where you're going and end up tumbling your way down the staircase at night.

<div class="row1">
  <div class="column1">
    <img onClick="location.href='https://i.imgur.com/cw3pBck.jpg';" src="https://i.imgur.com/cw3pBck.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column1">
    <img onClick="location.href='https://i.imgur.com/FSKsBPp.jpg';" src="https://i.imgur.com/FSKsBPp.jpg" alt="Forest" style="width:100%">
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
</style>

- Our refined sketches displayed different variations of sorting machines. One particular idea was a change sorting machine that would filter each coin into the appropriate bin depending on the weight of the coin. For instance, a quarter weighs differently than a dime, based off the result it would sort the coin into a particular bin for quarters, dimes, or any other change for that particular currency.

- As a team, we decided to go with a candy sorting machine after lengthy discussions for two reasons, the comedic value of sorting candy based off colour to eat specifically your favorite colour. As for the second reason, there are certain brands of candy that have different flavours depending on the colour. It would be a lot easier to avoid less favorable flavours if you are able to easily sort them out.


- These refined sketches showcase the implementation of our colour sorter machine more clearly. For the full refined sketches album, click this [**album**](https://imgur.com/a/JHGOMpM) link to be redirected.

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

<center><b>Color Sorting Machine Sketches</b></center>

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
</style>

#### Implementation

- In this implementation phase, we utilized the Arduino IDE and C++ to write, compile, and test our code. As shown in the video demonstration, the user would have to place each piece of candy one-by-one, the colour sensor attempts to detect the colour of the candy. Next, it would rotate the delivery system using the servo motor, and drop it into the appropriate bin.

<center>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/ThXtR1ksnCI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<center><b>Video Demonstration</b></center>



<hr>
<hr>

#### Source Code

- Download the source code from [GitHub](https://github.com/muhannadnouri/CPSC_581-Assgn2)

#### Contributors

- Alexander Lam
- Joseph Gorospe
- Michael Verwaayen
- Mitchell Rudy
- Muhannad Nouri