# What does componentDidMount do?
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

![1](https://miscoder.com/wp-content/uploads/2020/09/Stateful-vs-Stateless-Component-Tutorial-Component-with-state-768x398.jpg)

## What are props?
Props is short for properties and they are used to pass data between React components. React’s data flow between components is uni-directional (from parent to child only).
## What is the thing called ‘state’ in react js?
Just like props, state is another special built-in object in React, that allows components to create and manage their own data. In other words, state holds some information that is private to the component. The information is nothing but the observable properties that control the behaviour of that particular component. This information may change over the lifetime of the component. Every time it changes, our component re-renders.
## React State Vs Props.
![2](https://res.cloudinary.com/practicaldev/image/fetch/s--IeH7-Hx3--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/http://live-linguine-code.pantheonsite.io/wp-content/uploads/2019/03/react-state-vs-props.jpg)