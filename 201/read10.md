# Error Handling & Debugging
## Introduction
In an ideal world everyone would write perfect code and there would never be any need to debug. However in reality, virtually every project is going to require some degree of debugging. The more complex the project the more like this is to be true. Fortunately LiveCode includes a full plethora of debugging tools and techniques that make it quick and easy to track down errors. The live run-edit cycle allows you to see the effect of corrections as soon as you make them. And, unlike working in a lower-level language, when you make a mistake you will receive a human-friendly error message pointing you to where the error occurred, instead of the application unexpectedly quitting.
![1](https://bugfender.com/wp-content/uploads/2020/09/Featured-scaled.jpg)
**As well as the set of built-in error reporting and debugging tools, LiveCode also allows you complete flexibility over error handling, allowing you to provide a customized experience to the end user of your application.**

## Common Techniques for Solving Problems
If you encounter a problem with your code, there are a number of methods available to help you track it down. In this section we detail some of the main techniques you may find useful.

## Errors During Compiling
A Script Error occurs when your script cannot be compiled because of a syntax error. This is flagged up in the script editor when you attempt to compile a change to a script by pressing the Apply button in the Code Editor. Correct the error then press the Apply button to compile the script again.
![2](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)