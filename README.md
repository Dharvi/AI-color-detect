# AI-color-detect
In here I will be writing out some code to detect top colours in an image using ML and display the stats

So color extraction from images. Sounds cool ha!

Recently while working with a color picker extension for chrome an idea came into my mind that wouldn't it be great if I could just upload an image into a software or website and that software or website pulls out all different colors being used in that image and shows me some stats about an image lets say a pie chart.

So, I began to go deep into it and realised that in a normal color picking extension in chrome or normal tools we gotta select some part of the image and that tool basically pulls out the color in that part of the image. It means doesn't consider how the colors are distributed through out the image. 

A bit more deeper into it and some searches over the web brought me to the idea that our very own AI and ML based algorithms can be helpful here. An algorith such as "KMeans" clustering is a perfect fit for this kind of situation where we dont have any kind of idea for how the colors are going to be distributed within that image.

So, I had a background now on how to solve this kinda problem. Now it was time to CODE!!!

So, I started off with :-
  - Anaconda (I wrote the code in a Jupyter notebook)
  - Installed OpenCV using Anaconda itself (it was super easy. Believe me)
  - Other libraries and packages which I used includes:- SKLearn, Matplotlib, Numpy, Collections, skimage (can be used, although I haven't) and os module.
  - Jumped write into the code 

and Results were just wow !!!
Have a look into the Jupyter Notebook I ahve uploaded and you will see it!

After having a look into it what do you feel could be the use cases of it?
Well I will share what I feel for example:-
- Such an algorithm can be used if we want to create a fun website where you could just upload an image and have a look into its color distribution.
- We can use it in application where we 1000s of images and we wanna look for an image with specific color in it, let's say Blue may be.
- We can create an image separator feature for our devices which will differentiate images based on colors and collect them in separate places so taht if we wanna look for all images containing blue we can have it separated out.
- etc. :)





