# Angular-vs-React

### Angular vs React: What to Choose for Your App?

Some people say that comparing React and Angular is like comparing apples to oranges. While one is a library that deals with views, the other is a full-fledged framework.

Angular comes with data-binding bundled in, whereas React today is usually augmented by Redux to provide unidirectional data flow and work with immutable data. 

A mutable object is an object whose state can be modified after it is created. An immutable object is an object whose state cannot be modified after it is created. ... 

Examples of native JavaScript values that are mutable include objects, arrays, functions, classes, sets, and maps.

One-way data binding means that React is more performant than Angular and also makes debugging a React app easier than debugging an Angular app, in my opinion.

A unidirectional data flow means that when designing a React app you often nest child components within higher-order parent components. The parent component(s) will have a container for the state of your app (typically an immutable variable called state, unless you are using Redux or Flux, in which case you would encapsulate your app’s state in a store).

The parent component typically passes down a snapshot of its state to its child components via read-only props and then the child components can communicate with the parent to update the state via callbacks which are bound to a button or form in the child component.

Both Angular and React have component-based architecture, which means they have cohesive, reusable and modular components. But, the difference comes at the point of tech stack. React uses JavaScript while Angular goes with Typescript for web development which is more compact and error-free

Angular is a complete framework while React is a JavaScript Library. Angular uses a two-directional data flow process where it updates the Real DOM directly while React updates only the Virtual DOM and is concerned with the one-directional data flow. While React can be bundled with other programming libraries, Angular is a complete solution in itself. For uni-directional data flow, React needs to be augmented by Redux.

Framework Vs. Library
Learning Curve
Community Support
Developer's Perspective
Backward Compatibility

Brief Overview

React
React is a framework for UI development, so apps written with React need additional libraries to be used. For instance, Redux, React Router, or Helmet optimize the processes of state management, routing, and interaction with the API. Such functions as data binding, component-based routing, project generation, form validation, or dependency injection require additional modules or libraries to be installed.

Angular
Angular is a full-fledged framework for software development, which usually does not require additional libraries. All the above-mentioned functions – data binding, component-based routing, project generation, form validation, and dependency injection – can be implemented with the means of Angular package.

Universality

React
React is a framework used in both web and mobile development. However, for mobile development, it needs to be incorporated with Cordova. Moreover, for mobile development, there is an additional framework – React Native.
React can be used to build both single-page and multiple-page web applications.

Angular
Angular is suitable for both web and mobile development. In mobile development, however, a great share of work is done by Ionic. Furthermore, similarly to React, Angular has an additional mobile development framework. The counterpart of React Native is NativeScript.
Angular can also be used for both single- and multiple-page web apps.

Self-Sufficiency

React
React is a JavaScript library for UI development. It is managed by Facebook and an open-source community of developers.

The framework was introduced in May 2013.

The latest updates were released on August 8th, 2019 – just over a month ago.

Angular
Angular is an open-sourced JavaScript framework for web and mobile development. It is TypeScript-based and managed by Google’s Angular Team and the Angular developer community.

Launched in September 2016, Angular (also known as Angular 2.0) is a complete rewrite of AngularJS (Angular 1.0), which was introduced in 2010.

There have been six versions of Angular already, and the latest release took place on August 28th, 2019 – almost three weeks ago.

Learning Curve

React
React is minimalistic: no dependency injection, no classic templates, no overly complicated features. The framework will be quite simple to understand if you already know JavaScript well.

However, it takes quite some time to learn how to set up a project because there is no predefined project structure. You also need to learn the Redux library, which is used in more than half of React applications for state management. Constant framework updates also require additional effort from the developer. Furthermore, there are quite a lot of best practices in React, which you will need to learn to do things right.

Angular
Angular itself is a huge library, and learning all the concepts associated with it will take much more time than in the case of React. Angular is more complex to understand, there is a lot of unnecessary syntax, and component management is intricate. Some complicated features are embedded into the framework core, which means that the developer cannot avoid learning and using them. Moreover, there are a lot of ways of solving a single issue.

Although TypeScript closely resembles JavaScript, it also takes some time to learn. Since the framework is constantly updated, the developer needs to put some extra learning effort.

Community

React
React framework is one of the most popular JS frameworks worldwide, and the community supporting and developing it is huge.

Working with React, you have to be a continuous learner since the framework is often updated. While the community tries to go forward with the latest documentation as swiftly as possible, keeping up with all the changes is not that easy. Sometimes, there may be a lack of documentation, but the issue is often solved by the community support on thematic forums.

React is actively used by such companies as Facebook, Twitter, Netflix, Airbnb, PayPal, The New York Times, Yahoo, Walmart, Uber, and Microsoft.

Angular
Angular is less admired than React and faces a lot of skepticism, partially because of the unpopularity of Angular 1.0. Developers used to dismiss the framework as an overly complicated one as it required a lot of time to be spent learning. However, this framework has been developed by Google, which works in favor of Angular’s credibility.

Google provides the long-term support of the framework and constantly improves it. However, the updates are so fast that the documentation often falls behind.

Angular is used by such companies as McDonald’s, AT&T, HBO, Apple, Forbes, Adobe, Nike, and Microsoft as well.

Performance

React
React’s performance is greatly improved with the introduction of the virtual DOM. Since all virtual DOM trees are lightweight and built on server, the load on browser is reduced. Furthermore, since the data-binding process is unidirectional, bindings are not assigned watchers as in the case of Angular. Respectively, no additional workload is created.

Angular
Angular performs worse, especially in the case of complex and dynamic web apps.

The performance of Angular apps is negatively affected by bidirectional data-binding. Each binding is assigned a watcher to track changes, and each loop continues until all the watchers and associated values are checked. Because of this, the more bindings you have, the more watchers are created, and the more cumbersome the process becomes.

However, the most recent update of Angular has greatly improved its performance, and it does not lose to React anymore. Moreover, the size of an Angular application is slightly smaller than the size of a React app.

Language

React
React is based on JavaScript ES6+ combined with JSX script. JSX is an extension for syntax, which makes a JavaScript code resemble that written in HTML. This makes the code easier to understand, and typos are easier to spot. For the JSX code to be compiled in a browser, React is augmented with Babel – a code translation tool.

Angular
Angular can use JavaScript or TypeScript, which is a superset of JS developed specifically for larger projects. TypeScript is more compact than JavaScript, the code is easier to navigate, and typos are easily spotted. Code refactoring process also becomes simpler and faster.


App Structure

React
The structure of React provides developers with the freedom to choose. There is no “the only right structure” for a React app. However, the necessity to design the app structure at the beginning of each project makes it more difficult and longer to start.

Besides, React offers only View layer, while Model and Controller are added with the usage of other libraries.

The architecture of a React app is component-based. The code is made of React components, which are rendered with React DOM library and directed in two ways: functional (with a function that returns JSX) and class-based (with ES6 classes).

Angular
The structure of Angular is fixed and complex, suitable for experienced developers.

Angular is based on three layers – Model, Controller, and View. An object responsible for the Model is initialized by the Controller and displayed with the View.

The application code consists of different Angular components, each being written in four separate files: a TypeScript to implement the component, an HTML file to define the view, a CSS file to define the stylistic features, and a special file for testing purposes. Links to these files are written in the app directive, which displays the structural logic of the app. Respectively, Angular components are also reusable.

UI Components

React
UI tools for React are developed by the community. There are a lot of free and paid UI components on the React portal. To use material design components in React, you would have to install an additional library – Material-UI Library & Dependencies.

Angular
Angular has a built-in Material toolset, and it offers a variety of pre-built material design components. There are various buttons, layouts, indicators, pop-ups, and form controls. Because of this, UI configuration becomes simpler and faster.

10. Directives

React
In React, templates and logic are explained in one place – at the end of the component. It allows the reader to quickly grasp the meaning of the code even if they do not know the syntax.

Angular
In Angular, each template is returned with an attribute – a directive of how the object has to be set. The syntax of Angular directives is complex and sophisticated, which makes it incomprehensible for a reader without any experience in working with this technology.

State Management

React
In React, each component has its own state. A React developer can create special components for holding the state of the entire application or a particular part of it. The major disadvantage here consists in the fact that the global state needs to be stored in multiple different parts of the app with data being manually passed around different component tree levels.

To solve this problem, there is a special state management library – Redux. The idea of it is that the global state is represented as a single stateful object, which is altered in different parts of the app with the help of reducers – special Redux functions.

Another solution is offered by the state management library MobX. Unlike Redux with the global state stored in a single immutable stateful object, MobX offers storing only the minimal required state, while the rest of it can be derived.

Angular
In Angular, component data is stored in component properties. Parent components pass data through to children ones. State changes in some parts can be identified and recalculated, but in a large app, it can cause a multi-directional tree series of updates, which will be difficult to track. The features can be improved with the help of state management libraries, such as NgRx or RxJS , which would make sure that the data flow is unidirectional.

Dependency Injection

React
React does not fully support dependency injection as it does not fully comply with the idea of functional programming and data immutability. Instead, it has a global state for all components.

Angular
The greatest advantage of Angular rests in the fact that, unlike React, it supports dependency injection. Therefore, Angular allows having different lifecycles for different stores.

Data Binding

React
Data binding stands for the data synchronization process between Model and View. React should be augmented with Redux, which allows you to work with immutable data and makes data flow unidirectional. Unidirectional binding is predictable, which facilitates the debugging process.

Angular
Angular works with bidirectional data-binding and mutable data. While the advantages of mutable and immutable data are a matter of a heated discussion, it is definitely easier to work with bidirectional data-binding rather than with the unidirectional approach. At the same time, bidirectional data-binding negatively affects the performance since Angular automatically develops a watcher for each binding.

The ways of data-binding in Angular:

Change Rendering

React
React uses a virtual Document Object Model (DOM), which enables easily implementing minor data changes in one element without updating the structure of the entire tree. The framework creates an in-memory cache of data structure, computes the changes, and efficiently updates the DOM displayed in the browser. This way, the entire page seems to be rendered on each change, whereas actually, the libraries render changed subcomponents only.

The React team is constantly improving Fiber – a mechanism aimed at boosting the productivity of change rendering.

Angular
Angular uses a real DOM, which updates the entire tree structure even when the changes have taken place in a single element. The real DOM is considered to be slower and less effective than the virtual DOM.

To compensate for this disadvantage, Angular uses change detection to identify components that need to be altered. Therefore, the real DOM on Angular performs as effectively as the virtual DOM on React.

Tools

React
React is supported by multiple code editors. For instance, the code in React can be edited with Sublime Text, Visual Studio, and Atom. To bootstrap a project, you can use the Create React App (CLI) tool. In turn, server-side rendering is completed with the use of Next.js framework.

To test the entire app written in React, you would need multiple tools. For instance, Enzyme for component testing, Jest for testing JS code, React-unit for unit testing and so on. To debug the app in the development mode, you can use a browser extension React Dev Tools.

Another interesting tool is React 360, which is a library used for creating AR and VR applications.

Angular
Similarly to React, Angular is supported by a variety of code editing tools. For example, you may work with such code editors as Aptana, Sublime Text, and Visual Studio. A project can be promptly set up with Angular CLI. Server-side rendering is completed with the help of Angular Universal.

Unlike React, Angular can be fully tested with a single tool. For the end-to-end testing in Angular, the platforms are Jasmine, Protractor, and Karma. Another tool that debugs the app in the development mode is a browser extension Augury.

To Wrap Up
Angular is a full-fledged mobile and web development framework. React is a framework only for UI development, which can be turned into a full-fledged solution with the help of additional libraries.

React seems simpler at first sight, and it takes less time to start working on a React project. However, simplicity as the outspoken advantage of React is neutralized with the necessity to learn to work with additional JavaScript frameworks and tools. Angular itself is more complex and takes quite some time to master. Yet, it is a powerful tool that offers a holistic web development experience, and once you learn how to work with it, you reap the fruits. 

There is no better framework. Both are updated continuously to keep up with the competitor. For instance, while React was believed to win because of its virtual DOM, Angular equaled the score by implementing change detection. While Angular was considered to be winning because of being developed by such an authoritative company as Google, the immense devoted React community fully compensated for Google‘s reputation and made React similar to Angular.

Eventually, React vs Angular is all a matter of personal preference, a matter of skills and habits. As a beginner in programming, you would probably benefit more from starting with React. As an experienced developer, you just keep working with what you know better. Do not forget to challenge yourself and start learning a new framework, React or Angular. As a Project Manager or a business owner outsourcing developers, you should talk to your web development team and together choose the framework that suits all of you best, would it be Angular or React.
