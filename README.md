
##Steps of running this project

from the command prompt clone the project

* $git clone https://github.com/JaliyaFernando/State-and-Props-in-ReactJS.git
* $cd react-understanding-state-props
* $npm install
* $npm start

State-and-Props-in-ReactJS

React provides basically two ways that data gets handled these are States and Props. State and props makes react dynamic. State does it from inside and props does it from outside.

React State 

State is an instance of React Component Class that holds some data or information that may change over the lifetime of the component. To use state the component must be a class-based component and there must be a constructor in the class.Because state of a component may change throughout the lifetime, so you need to define initial state of the component inside of the constructor."this.state" use to assign values which by default is null so by default state will be null. State can not be update explicitly. Because as the state an observable object use in react.So if we update state of a component like this web page will not re-render itself because react state cannot able to detect the changes made.So to update state of a component react provides its own method setState(). setState is the most important method in react. After the update of the state its implicitly calls the render() method to re-render the page.setState method is asynchronous so, if you want to use state and props inside setState method use second form of the method. 
 

React Props

Props is what you pass into a component from outside of it. Props are equivalent to parameters of a pure JavaScript function. Props are immutable. Because props are are developed in the concept of pure functions in pure functions we cannot change the data of parameters.


Props vs State
Props are immutable, can not be change. State can change over time also control the behavior after each change.
State can only be use in Class Components only but Props don not have that limitation.
Props are set by the parent components. State is generally update by event handlers. 

