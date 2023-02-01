># React Js

* Since you are here reading this article on React js  so you might have a slight idea about what ReactJs is! ( Don't worry we will go in deep as well!)

### Here's an interesting fact to start on :
* Do you know __Why React Js is termed React__ ?
* The reason is because of the way it reacts quickly with its best friend Virtual DOM! Isn't interesting?
* So let's let's dive deep and see formally what ReactJs is....

### What's new?
* You can build web apps that can play around with data simply, without refreshing the page.
* Isn't cool? No more link refreshing process to navigate, on a button click, on a entry. Its __React without Refresh!__

### Now let me formally introduce React Js :
* React Js is an open-source, component-based light-weighted front end library concerning about the view layer of the application. Let me focus again :
1. Open source
2. Component Based
3. Lightweight
* It builds user interfaces primarily based on UI components.
* This follows Model View Controller (MVC) architecture.
* It is maintained by Meta and a community of individual developers and companies giving it enormous developer's support and huge community base.

># History

* A prototype called "FaxJs" was released by `Jordan Walke`, a software engineer at Meta (formerly Facebook) around 9 years ago.
* Its a fastest blooming open-source library specifically based on Components.
* The craze with XHP, a HTML based framework for PHP had a great impact on React.
* React debuted with newsfeed application in 2011.
* Later, many companies around used it and customized into their applications.

># Confusing but Simple React Facts
* Though these are often second thought givings, you will be comfortable with such topics after reading the following. So lets get started.

### 1. Library or Framework?
* You will hear professionals saying React is a framework. But NO! `React is a library` according to official document.
* The reason why even professionals get confused lies in the fact that React has several characteristics of a framework.
* All libraries are collections of definitions and on calling a method in the library, then its in your control.
* However, framework themselves define the control flow while calling your code.
* Frameworks aim at structural complexities resolution. On the contrary, React only provides methods to enhance front-end management and development.

### 2. HTML and JSX
* JSX explodes to Javascript Extension Syntax which allows us to write HTML and JavaScript together. Yes you heard it right! Together!
* We can say `JSX = JS + HTML`
* Still don't believe here's an example
```js
const jsx = <h1>Hi I am JSX!</h1>
```
* JSX is the strength of React.
* For browser though there's nothing like JSX. So there's another friend in help called Babel which is a Javascript compiler/transpiler which converts JSX easily written by developers into machine understandable code.
* So earlier example for browser is like:
```js
React.createElement(
  'h1',
  null,
  'Hi I am JSX!'
)
```

### 3. Multidirectional or Unidirectional
* React has the concept of `Unidirectional Data Flow`.
* This means data has one and only one way to be transferred to other parts of the application.
* There are many advantages of react being unidirectional flow. Some of them are :
* Convinient debugging - you can easily keep track of how it is processing.
* Better control - Code becomes less prone to error.
* Efficiency - Extra resources and are not wasted being only one way flow

### 4. DOM and Virtual DOM
* DOM implies Document Object Model.
* Manipulating DOM is slow. Manipulating virtual DOM is much faster.
* In React, for every DOM object, there's a corresponding "virtual DOM object".
* Virtual DOM being a DOM object representation, its nothing but a lightweight copy of DOM.
* Think it as Painting only one wall of a house directly, rather than moving across various rooms of house to reach that wall and paint.
* What technically happens is, whenever there's a change somewhere in the website. New virtual DOM compares it with a pre updated version and changes only that part. It does this with a process called `diffing` in which it checks exactly which object has been changed. However actual DOM bring updates entire object making it slow.


># Properties of React
## 1. JSX - JavaScript Syntax Extension
Enabling HTML and Javascript to be written together.

## 2. Unidirectional Data Flow
Concept of Flux make such flow possible making it super advantageous.

## 3. Virtual Document Object Model (VDOM)
Making React lightweight and faster giving it best memory representation.

## 4. Extensions
React supports wide variety of extensions - supporting server side rendering, flux, redux widely in developments.

## 5. Debugging
React being open  source has huge community support. Testing has become very easy with such support and extensions.

## 6. Conditional Statements
With great use of JSX it allows us to write conditional statements making display as the cases.

## 7. Component Oriented Architecture
React divides web page into multiple components with its own logic and design making it easy to write and debug, run faster and reusable.

## 8. Declarative UI
This feature enables react code to be easily readable and debuggable. That  too UI are not just for web but for mobile as well with React Native
># React Js

* Since you are here reading this article on React js  so you might have a slight idea about what ReactJs is! ( Don't worry we will go in deep as well!)

### Here's an interesting fact to start on :
* Do you know __Why React Js is termed React__ ?
* The reason is because of the way it reacts quickly with its best friend Virtual DOM! Isn't interesting?
* So let's let's dive deep and see formally what ReactJs is....

### What's new?
* You can build web apps that can play around with data simply, without refreshing the page.
* Isn't cool? No more link refreshing process to navigate, on a button click, on a entry. Its __React without Refresh!__

### Now let me formally introduce React Js :
* React Js is an open-source, component-based light-weighted front end library concerning about the view layer of the application. Let me focus again :
1. Open source
2. Component Based
3. Lightweight
* It builds user interfaces primarily based on UI components.
* This follows Model View Controller (MVC) architecture.
* It is maintained by Meta and a community of individual developers and companies giving it enormous developer's support and huge community base.

># History

* A prototype called "FaxJs" was released by Jordan Walke, a software engineer at Meta (formerly Facebook) around 9 years ago.
* Its a fastest blooming open-source library specifically based on Components.
* The craze with XHP, a HTML based framework for PHP had a great impact on React.
* React debuted with newsfeed application in 2011.
* Later, many companies around used it and customized into their applications.

># Confusing but Simple React Facts
* Though these are often second thought givings, you will be comfortable with such topics after reading the following. So lets get started.

### 1. Library or Framework?
* You will hear professionals saying React is a framework. But NO! `React is a library` according to official document.
* The reason why even professionals get confused lies in the fact that React has several characteristics of a framework.
* All libraries are collections of definitions and on calling a method in the library, then its in your control.
* However, framework themselves define the control flow while calling your code.
* Frameworks aim at structural complexities resolution. On the contrary, React only provides methods to enhance front-end management and development.

### 2. HTML and JSX
* JSX explodes to Javascript Extension Syntax which allows us to write HTML and JavaScript together. Yes you heard it right! Together!
* We can say `JSX = JS + HTML`
* Still don't believe here's an example
```js
const jsx = <h1>Hi I am JSX!</h1>
```
* JSX is the strength of React.
* For browser though there's nothing like JSX. So there's another friend in help called Babel which is a Javascript compiler/transpiler which converts JSX easily written by developers into machine understandable code.
* So earlier example for browser is like:
```js
React.createElement(
  'h1',
  null,
  'Hi I am JSX!'
)
```

### 3. Multidirectional or Unidirectional
* React has the concept of `Unidirectional Data Flow`.
* This means data has one and only one way to be transferred to other parts of the application.
* There are many advantages of react being unidirectional flow. Some of them are :
* Convinient debugging - you can easily keep track of how it is processing.
* Better control - Code becomes less prone to error.
* Efficiency - Extra resources and are not wasted being only one way flow

### 4. DOM and Virtual DOM
* DOM implies Document Object Model.
* Manipulating DOM is slow. Manipulating virtual DOM is much faster.
* In React, for every DOM object, there's a corresponding "virtual DOM object".
* Virtual DOM being a DOM object representation, its nothing but a lightweight copy of DOM.
* Think it as Painting only one wall of a house directly, rather than moving across various rooms of house to reach that wall and paint.
* What technically happens is, whenever there's a change somewhere in the website. New virtual DOM compares it with a pre updated version and changes only that part. It does this with a process called `diffing` in which it checks exactly which object has been changed. However actual DOM bring updates entire object making it slow.


># Properties of React
## 1. JSX - JavaScript Syntax Extension
Enabling HTML and Javascript to be written together.

## 2. Unidirectional Data Flow
Concept of Flux make such flow possible making it super advantageous.

## 3. Virtual Document Object Model (VDOM)
Making React lightweight and faster giving it best memory representation.

## 4. Extensions
React supports wide variety of extensions - supporting server side rendering, flux, redux widely in developments.

## 5. Debugging
React being open  source has huge community support. Testing has become very easy with such support and extensions.

## 6. Conditional Statements
With great use of JSX it allows us to write conditional statements making display as the cases.

## 7. Component Oriented Architecture
React divides web page into multiple components with its own logic and design making it easy to write and debug, run faster and reusable.

## 8. Declarative UI
This feature enables react code to be easily readable and debuggable. That  too UI are not just for web but for mobile as well with React Native


To clear more such topics and diving deep Stay Connected!
Happy Learning :}

To clear more such topics and diving deep Stay Connected!
Happy Learning :}
