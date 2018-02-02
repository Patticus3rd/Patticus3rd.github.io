---
layout: post
title: Mario Pest Control Project!

---



This project was our first individual project. My game plan for this project was just to keep it as organized as possible
so I could understand the components of each individual element.  Overall I had a great time building this and implemented
more Bad Guys for Mario to catch!

![MARIO PROJECT IMAGE](https://patticus3rd.github.io/images/mario_project.png)

## Goal:
The Goal set for this project is to implement Javascript into a simple HTML Page.  The overall theme for the project is to create a Counter for Mario when catching Baddies. 

## Highs:
I had a lot of fun doing this project since it was Mario Themed.  One of the light bulb moments I had was when I had trouble outputing the Counters.  The variables that I had in each function to update the counter would **update** the counter however it did not update the counter because when the server reads the JS file, it would just update the counter in JS but not on the HTML file.  I had to call the update and also call ```totalMagiKoopa.innerHTML = "Caught:" + totalBaddie2;``` after each individual counter update to make it look like this:
```javascript
function addGoomba() {
    counter += 5;
    totalBaddie1++;
    output.innerHTML = "The total is: " + counter;
    totalGoomba.innerHTML = "Caught:" + totalBaddie1;
}

function addMagiKoopa() {
    counter += 7;
    totalBaddie2++;
    output.innerHTML = "The total is: " + counter;
    totalMagiKoopa.innerHTML = "Caught:" + totalBaddie2;
}
```

## Lows:
The hard part about this project was keeping track of the file systems. I had a hard time trying to style each individual component.  Originally I had set the images in a folder and got really confused. Looking back, I would definitley still use folders because I can keep better track of them now.
![MARIO GIF](https://patticus3rd.github.io/images/mario_gif.gif)



