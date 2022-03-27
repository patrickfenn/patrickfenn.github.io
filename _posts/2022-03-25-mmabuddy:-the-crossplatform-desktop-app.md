---
layout: post
title: MMABuddy - The Cross Platform desktop app for MMA fans!
subtitle: This app was coded in python utilizing the kivy library. 
cover-img: /asssets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [python, kivy]
---

MMABuddy is an app I made for myself because I found it troublesome to be up to date on all the MMA events I was interested in. I chose to use python because I recently completed coursework for a ML class that used it and I enjoyed it. I chose Kivy because tkinter seemed pretty limited and the cross-platform aspect intrigued me. 

Interesting things I used to program the app:
* Beautiful soup to parse a website for the necessary event details.
* Regex for identifying each event.
* Dynamically detect timezones using python libraries and convert from the posted time to the user's time. 

I plan on extending it to work on android. One issue though is some python libraries do not run natively on android so some compatibility issues became apperent. Since Kivy essentially packages the related python libraries into an executable.
