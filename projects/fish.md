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
