+++
date = "2019-02-24"
title = "CPSC 581 - Assignment 1"
math = "true"

+++

## Context

In this project, we were tasked to implement an alternative to the traditional slide to unlock feature originally found in Apple's iPhone and later alternative implementations in many different Android phones. The first task was to implement an alternative that utilized the smartphone's many sensors, and the second tasks was to implement an alternative that involved the smartphone's touch display in some form.

<hr>

## Design One - Touch Unlock

#### Sketch Design Phase

- These were the initial of when I was brainstorming ideas for a touch unlock alternative. When I was searching for ideas for a touch unlock alternative, I attempted to focus on a unified theme for both the touch and sensor unlock versions. This was reflected in some of my sketches where the majority had a Harry Potter themed idea.
<center><img src="https://i.imgur.com/7RyuRk3.jpg" alt="drawing" align="middle" width="60%"/></center>
<center><b>Initial Sketches</b></center>

- These are the refined sketches that we came together as a group when it came to the touch unlock alternative. In this case, after many rounds of feedback, we decided to recreate my own personal hell of clicking on advertisements on your phone in the correct order to make the ads go away in order to unlock your phone.
- If you did happen to click the ads in the incorrect order, you are subjected to more commercials including a 50 second video that you have to watch before returning to the main screen in order to try again.
<center><img src="https://i.imgur.com/PwROOwT.jpg" alt="drawing" align="middle" width="60%"/></center>
<center><b>Refined Sketches</b></center>

#### Implementation

- In this implementation phase, we utilized Android Studio to build an Android application as a proof of concept for our ideas. As shown in the video demonstration, the user would have to click through seven different advertisements in order to unlock their phone.

<center>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/xMwIyFzVys0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<center><b>Video Demonstration</b></center>



<hr>
<hr>


## Design Two - Sensor Unlock

#### Sketch Design Phase

- In my initial sketches, I focused a lot of my idea generation on the touch unlock alternative. Therefore, when it came to the sensor unlock alternative one of my best ideas that I decided to depict were squeezing the phone to unlock, and to draw your initials in the air.
<center><img src="https://i.imgur.com/CVW1vKv.jpg" alt="drawing" align="middle" width="60%"/></center>
<center><b>Initial Sketches</b></center>

- These are the refined sketches that we came together as a group when it came to the sensor unlock alternative. In this case, after many rounds of feedback, we decided to recreate the motion of using a physical key to unlock your phone.

- In this case, the user would have to pick the correct key from a set of seven different keys. Once the correct key was chose, they would to perform the motion of turning a key in order to unlock their phone.

<center><img src="https://i.imgur.com/KWZtHQb.jpg" alt="drawing" align="middle" width="60%"/></center>
<center><b>Refined Sketches</b></center>

#### Implementation

- In this implementation phase, we utilized React Native to build an Android or iOS application as a proof of concept for our ideas. As shown in the video demonstration, the user would have to choose the correct key to unlock their phone and perform the key unlocking motion.

<center>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/-o7-d0jJUZw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<center><b>Video Demonstration</b></center>

<hr>
<hr>

## Source Code

- Download the source code from [GitHub](https://github.com/muhannadnouri/CPSC_581-Assgn1)

## Deployment

##### Touch Unlock
- Navigate to the [MyApplication](https://github.com/muhannadnouri/CPSC_581-Assgn1/tree/master/MyApplication) directory on the GitHub repository.
- To run the application, download [Android Studio](https://developer.android.com/studio/) from the official website.
- Choose <b>Pixel 2 XL</b> as the emulator device running Android 9, API 28
- Alternatively, connect your Android phone to the computer and select it as the target device

##### Sensor Unlock
- Navigate to the [SensorApplication](https://github.com/muhannadnouri/CPSC_581-Assgn1/tree/master/SensorApplication) directory on the GitHub repository.
- To run the application, download the APK file [CPSC581Key.apk](https://github.com/muhannadnouri/CPSC_581-Assgn1/blob/master/SensorApplication/CPSC581Key.apk) from the GitHub repository.
- Install the APK file on your Android device


#### Contributors

- Alexander Lam
- Joseph Gorospe
- Michael Verwaayen
- Mitchell Rudy
- Muhannad Nouri