---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Kawailoa Solar Curtailment Project"
date: 2022-07-22
published: true
labels:
  - Renewable Energy
  - Python
  - Cost Analysis
summary: "The Kawailoa Curtailment Project was a cost analysis project using a Python to develop a program that would calculate total energy loss throughout the year based on curtailment data and proposed the development of a Battery Energy Storage System to recover over 23 million dollars of potential revenue."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

The Kawailoa Solar Curtailment Project was a result of my six-week internship at Clearway Energy Hawaii located out in Mililani. The internship provided valuable lessons, experience, and connections to the renewable energy industry which was culminated to a final project presentation at the end of internship program with a proposed solution to an aspect of the company that I was interested in.

For this project, I received the mentorship from Jeffrey Craft, a Data Analytics Manager at Clearway Energy. With his guidance, I was able to receive curtailment data from the past year in order to calculate the total lost energy and potential revenue from all the lost energy due to curtailment. This information combined with a power purchase agreement with HECO, a total figure was obtained and a proposed solution was designed specifically for the Kawailoa Solar Farm out in the North Shore.

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
