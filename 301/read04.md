## Things I want to know more aboutReact Docs - Forms

### Forms
HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state.  
![2](https://drek4537l1klr.cloudfront.net/thomas/Figures/05fig04.jpg)
## Controlled Components  
+ In HTML, form elements typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

+ We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.
for example
![1](https://miro.medium.com/max/1400/1*3iHnKaQK64ClycpGikpnIA.png)