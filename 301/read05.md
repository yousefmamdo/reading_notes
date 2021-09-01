## Component Hierarchy
React allows us to break the user interface into logically connected components. Those components when combined make a complete application structure.
***But, if you are a beginner in the React world, you will find yourself stuck at how to approach a layout design and break it into react components. Breaking the application into components is the first and the most crucial step in building a react application. A good structure makes your app scalable, maintainable and testable.***
In this article, we are going to learn how to —
+ Break a layout into react components
+ Convert those components into a component hierarchy
![1](https://cdn-images-1.medium.com/max/1600/1*A8ds6m4es9z3ZRWwbb2NXQ.png)
## single responsibility principle

+ The single responsibility principle says that each of our classes has to be only used for one purpose.

+ We need this so that we don’t have to change code as often when something changes. It’s also hard to understand what the class is doing if it’s doing many things.

+ Unrelated concepts in the same class also make comprehending the purpose of the code harder.
![2](https://hackernoon.com/_next/image?url=https%3A%2F%2Fcdn.hackernoon.com%2Fimages%2F0*BexdX1vV22goA_xR.gif&w=1080&q=75) 
## What is a Static App?
+ Static applications and websites render in the user’s browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies. Whilst traditionally managing static websites and applications may seem like hard work, the medium has come on leaps and bounds over the past few years to the extent that it’s now perfectly feasible to run heavy content, rich media websites, and applications entirely in the browser – Good times!

+ So grabbing and rendering UI elements doesn’t need roundtrips to your server, instead relying on the browser, which actually saves a heck of time for the user.

## Why Should I Build a Static App?
+ Static apps are simpler, quicker to develop, and cheaper to host. In fact, it’s perfectly feasible to host your entire static app on a CDN.

+ Modern JavaScript frameworks like AngularJS can be used to quickly build your site’s front-end, then hooked up to back-end data services like Firebase, allowing you to quickly sketch out what your interface looks like and turn it into a functioning prototype.

## Using State

Say a customer places an online order for a TV. While this order is being processed it can in one of many states: New, Approved, Packed, Pending, Hold, Shipping, Completed, or Canceled. If all goes well the sequence will be New, Approved, Packed, Shipped, and Completed. However, at any point something unpredictable may happen, such as no inventory, breakage, or customer cancelation. If that happens the order needs to be handled appropriately.

![3](https://www.dofactory.com/img/diagrams/javascript/javascript-state.jpg) 