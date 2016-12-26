---
layout: post
title: You're up and running!
---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

``` r
#Create WorkOut Log Table
playernum <- c(34,16,13,22,34,13,9,7)
dateofwrkout <- c("1/26/1983","1/30/1983","1/4/1983","1/6/1983","1/8/1983","1/24/1983","1/14/1983","1/18/1983")
exercise <- c("bench","bench","deadlift","bench","deadlift","squat","squat","deadlift")
weight <- c(50,90,40,110,30,60,130,150)
reps <- c(7,6,8,4,4,3,6,4)
workoutlog <- data.frame(playernum,dateofwrkout,exercise,weight,reps)
names(workoutlog) <- c("Player ID","Date of Workout","Exercise","Weight","Reps")
```
The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
