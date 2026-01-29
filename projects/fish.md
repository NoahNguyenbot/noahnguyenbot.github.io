---
layout: project
type: project
image: img/fishpond/Fishphoto.webp
title: "Fish Pond Game"
date: 2024
published: true
labels:
  - OOP
  - Java
summary: "My final project for ICS 211"
---

<div class="text-center p-4">
  <img src="/img/fishpond/IaGraph.png" class="img-fluid rounded shadow-lg mx-auto d-block" alt="Fish Pond Game screenshot">
</div>

My final project for ICS 211 involved us grouping up to make a fishing game with Java. The whole semester was actually based upon setting up this final project. Each weekly assignment throughout the semester had us create small parts of the project. This project involved a lot of topics including 

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
