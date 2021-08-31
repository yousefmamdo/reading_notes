#  map() method
## Definition and Usage
+ The map() method creates a new array with the results of calling a function for every array element.
+ The map() method calls the provided function once for each element in an array, in order.
+ map() does not execute the function for empty elements.
+ map() does not change the original array.  
![1](https://www.freecodecamp.org/news/content/images/2021/03/javascript-map-function.png)  

***Spread operator is useful for many different routine tasks in JavaScript, including the following:***
+ Copying an array.
+ Concatenating or combining arrays.
+ Using Math functions.
+ Using an array as arguments.
![2](https://res.cloudinary.com/practicaldev/image/fetch/s--IHKam6vP--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/cp0c15zovhapyiyq13zk.png)

+ var b utilizes an anonymous function
+ var c utilizes a named function
+ var d utilizes an arrow function  
***The .map() method does not mutate the original array. In the code above, a still evaluates to [1,2,3,4,5]. If you are not using the new array or if you are not returning any values from the callback, .forEach is probably the better option to use.***