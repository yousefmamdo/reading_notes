## Images
In the beginning, the Web was just text, and it was really quite boring. Fortunately, it wasn't too long before the ability to embed images (and other more interesting types of content) inside web pages was added. There are other types of multimedia to consider, but it is logical to start with the humble <img> element, used to embed a simple image in a webpage. In this article we'll look at how to use it in depth, including the basics, annotating it with captions using <figure>, and detailing how it relates to CSS background images.  
![img1](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVdPaWV2XJ1air5KWUt0-tgfCvGlwBmajjyz3KkBSz2WrdXGDkB4vAXg-uA9aSOB21dUM&usqp=CAU)
### Width and height
You can use the width and height attributes to specify the width and height of your image. You can find your image's width and height in a number of ways. For example on the Mac you can use Cmd + I to get the info display up for the image file. Returning to our example, we could do this:  
+ <img src="images/dinosaur.jpg"
     alt="The head and torso of a dinosaur skeleton;
          it has a large head with long sharp teeth"
     width="400"
     height="341">
  
  ## Practical Information    
  ### A tabbed info-box
    The first example we'll look at is a classic tabbed info box — a very common feature used when you want to pack a lot of information into a small area. This includes information-heavy apps like strategy/war games, mobile versions of websites where the screen is narrow and space is limited, and compact information boxes where you might want to make lots of information available without having it fill the whole UI. Our simple example will look like this once we are finished:  
 ![img1](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Practical_positioning_examples/tabbed-info-box.png)
