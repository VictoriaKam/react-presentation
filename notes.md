# REACT
Today I would like to tell you a little bit about React.

Nowadays React is the most popular JavaScript library for building User Interfaces. It was created in 2013 by Facebook developers. After that a React Native was created, so now React in not only for web, it allows you to create native mobile applications.

As for me, the most interesting question is “Why React is so popular?” I mean there are so many JavaScript libraries and they are created more and more every day. So what is the secret?
Well, there are a few reasons that we should talk about:
*	First of all, businesses that use React are assured of better performance compared to those that use other frameworks
*	Because React helps to prevent updating of DOM, it means that the apps will be faster and deliver better User Experience
*	React was designed to help improve the total rendered pages from the website server.

Ok, it sounds really good. But there are also many people who don’t like React at all. What are their arguments? Those people say that frameworks are bad for application's health and it’s better to use Web components instead. Well, `So many men, so many minds`. 

But as soon as it’s still so much popular, let’s talk about React basics.
React has component-based architecture, which means it has cohesive, reusable and modular components. With these components we can display data as it changes over time.

If you never used React before, the best way to start will be to install React Developer Tools on your browser extensions and check different websites that use React for their interfaces. You can inspect, for example, Facebook and see all of the different components that make up this page. So a React page is just a collection of components, and the React developer tools show us where these components live in the component hierarchy.  

To create your first React app, you need to install Create React App as a global dependency, using NPM. Then navigate to your project folder and run the command create-react-app that is going to generate a project, name your project and run npm start. Well, everything is ready now and we can start our first app. But what is inside this project folder? There are different dependencies that will help us to develop a functional app: react for creating components, react-dom for placing components in DOM and react-scripts for transpiling of new syntax into browser compatible.

There are several main definitions in React that everyone should know. The first one is Component. Component is  independent and reusable bit of code. We create a user interface simply by creating and nesting a collection of components. Components come in two types, Class components and Function components. Class component has to include the extends React.Component statement, this statement creates an inheritance to React.Component. It also requires a render() method, this method returns HTML. Components must start with an upper case letter. A Function component is a JavaScript function that returns JSX elements to be rendered.
Another important definition I should mention is JSX – JavaScript as XML - is an extension of the language which gives us possibility to use tags directly in JavaScipt. To use JSX you should add Babel to your app page.

Props are arguments passed into React components. Props are passed to components via HTML attributes. React Props are like function arguments in JavaScript and attributes in HTML.

React components has a built-in state object. The state object is where you store property values that belongs to the component. When the state object changes, the component re-renders. To change state you should use setState and to bind this you use arrow function.
Just like HTML, React can perform actions based on user events. React has the same events as HTML: click, change, mouseover etc. React events are written in camelCase syntax and inside curly braces.

The React component lifecycle provides functions that are invoked at specific times during the rendering lifecycle. It comes with 3 phases: mounting, updating and unmounting. So mounting and unmounting just means whenever component's added to the dom, and whenever it's taken away. Updating, when anything changes. 
Just like in HTML, React uses forms to allow users to interact with the web page. We add a form with React like any other element. When the data is handled by the components, all the data is stored in the component state.

When you're done putting together your project, you can post it online and you may want to create a production build to do that. Now you'll notice that when you run Create React App, it says to create a production build use npm run build. This is basically going to create an optimized build that's ready to post on something like Netlify or some other sort of hosting provider. So you should run npm run build.  The next thing that we can do though is we can serve it locally with a static server using an npm package called serve. So let's make sure that this is installed so we can run sudo npm install serve -g. And finally when this is installed, we can say serve -s build so we're going to serve the build folder and is is going to run this on localhost 5000. Everything is ready!

And one more interesting point I would like to mention before end – what is the difference between React and Angular? The difference comes at the point of tech stack. React uses JavaScript while Angular goes with Typescript for web development which is considered more compact and error-free.

Let's talk about it in details. Benefits of React over Angular are obvious: better user experience, time-saving, quick development, faster testing, code stability with
one-directional data binding. But which are benefits of Angular over React? Well, there are: cleaner code, thanks to using TypeScript, higher performance, material dsign-like interface, better error-handling, seamless updates using Angular Command Line Interface. So what to choose - React or Angular? It depends on many factors, like: what experience your team has, your app complexity, features etc.

So, that’s all for now. I hope this small video will push you to know more about React. Have a good day!
