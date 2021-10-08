2021-10-07-Project-Blog-Post
================
Jenna Wilkie
10/7/2021

For this project, I created a set of functions that would allow the user
to call data from multiple endpoints in the NASA API. Once I pulled the
data, I did some analysis looking for any interesting patterns or
trends.

One interesting thing I found was that the absolute magnitude of
asteroids has a strong negative correlation to the estimated diameter of
the asteroid. The absolute magnitude is the “brightness” of an asteroid
from a distance of 10 parsecs. So the larger the asteroid, the less
bright it appears.

Many of the objects that were returned from the API were lists that
contained both data frames and vectors. This posed a challenge when I
was formatting the data for analysis. It took me a little while to
figure out how to work with the data, then I spent even longer kicking
myself for not using the str() function to check it out sooner\!

Next time I do a project of this size, I’m going to spend more time
planning before I start coding. Things can get confusing really fast if
you don’t have a solid game plan before you start trying to create
functions and manipulate data. A better approach would be to spend some
time planning how to approach each aspect of the project first.

[Github-Pages](https://jwilkie94.github.io/ST558-Project-1/) [Regular
Repo](https://github.com/jwilkie94/ST558-Project-1.git)
