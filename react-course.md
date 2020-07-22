# React
### Before the course:
- You should have basic knowledge of JavaScript and HTML
- Be able to work with Git
- Join Discord chats https://discord.gg/Uazp6s, category REACT.

#### The course Trainers:
- Yuliya Haluza
- Artёm Sinicyn
- Alexey Farbotko
- Ander Rios
- Andre Gloukhmantchouk

#### Communication
For any questions use Discord.

# Learning Plan

## React. 1 Lecture. Webpack 

* Overview
* Webpack Config
* Plugins
* Loaders
* Webpack Dev Server

### Materials:
- [Lecture (video)](https://youtu.be/2ODZXRrEn28)
- [Slides](https://drive.google.com/file/d/10psw_ZPJYyT0Kkz-1vqLhsDyuSZgxTOu/view?usp=sharing)
- [Code Examples](https://github.com/yuliaHope/webpac-react/branches)
- Webpack screencast: https://www.youtube.com/playlist?list=PLOQDek48BpZFadeo_SJUNDggOKouA-nyM
-  Articles:
    https://github.com/webpack-contrib/eslint-loader#failonerror
    https://codeburst.io/react-bake-from-scratch-or-box-javascript-version-smackdown-8a4d31f105d7
    
## Task 1. Song Bird

https://github.com/rolling-scopes-school/tasks/blob/master/tasks/songbird.md

Form for questions: https://docs.google.com/document/d/1p7xsA6wgcWB_-27bsV2llLULlZR7lYcXvNR5VuEI4Ck/edit?usp=sharing

## React. 2 Lecture. Components (Main)

Form for questions: https://docs.google.com/document/d/1u86RSOAVfrSmiziIB3gXwI9yOw0Xty8QIvNG0GPB7FI/edit?usp=sharing

### 1 part
* What is react?
* Virtual DOM as approach to build fast UI components, Why V-DOM instead of direct DOM manipualtion
* JSX introduction
* the comoponent approach
* stateless, statefull components
* lifecycle hooks (React 16) and how they could be useful
* how to pass data to child components
* state. how to use it, how to change it (how react batches updates, async setState)
* how to handle DOM events
* how to create list, key prop
* conditional rendering

### 2 part (practice)
* react app creation from scratch
* webpack configuration 
* hello world stateless component (basic syntax, jsx)
* statefull counter component (event handling, ```this``` binding problem)
* users list component (key prop explained)
* TBA

### Materials:
- [Lecture (video)](https://youtu.be/xo66V7lrinU)
- [Slides](https://slides.com/yuliaka71/react-856420)
- Everything you want and may need to know about React: https://reactjs.org/
- Split app on components(examples):  https://drive.google.com/open?id=16kjgPAtIXpKKvpf4x_4-cbA_edWM01OT

## React. 3 Lecture. Components(Advanced)

Form for questions: https://docs.google.com/document/d/1UEm5-YvbDbyk75gvfeFjXS_PhP5cFQNzvztL99RR1_A/edit?usp=sharing

### 1 part
* Quick revison of Lecture #1
* Reconciliation algorithm
* propTypes and why it is important
* refs, uncontrolled components
* new context API
* advanced JSX (hoc, render prop, portal)
* lazy, suspense, memo
* performance optimisations

### 2 part (practice)
* todo app development
* add todo, remove todo
* mark todo as completed
* edit todo
* filter todos
* todos statistics (completed counter, uncompleted counter)
* TBA

### Materials:
- [Lecture (video)](https://youtu.be/WSK3MlZ-W4g)
- [Slides]()
- [Code Examples]()


## React. 4 Lecture. Hooks

Form for questions: https://docs.google.com/document/d/1Uz08VF7V33UHGB7-o4AMI-CMzyI1B-IspWwP1msRfco/edit?usp=sharing

* The useState Hook
* useState vs. setState
* Complex State with useState
* The useEffect Hook
* useEffect Dependencies
* Cleaning up Effects
* The useReducer Hook
* The Context API & useContext Hook
* TBA

## Task 2. Data Grid

https://github.com/rolling-scopes-school/tasks/blob/master/tasks/datagrid.md

Form for questions: https://docs.google.com/document/d/1KRc6ahRG6UW8CpvJm8OTySNqS9shP2sxSyuVTOD-pJw/edit?usp=sharing

## React. 5 Lecture. Routing

Form for questions: https://docs.google.com/document/d/1EYVxVrQMSYe7djvljAvcYtxtNvmFF6zL9_Psl85CeEc/edit?usp=sharing

### 1 part
* what is SPA
* React-router
* hash routing
* browser routing
* problems of SPAs
* TBA 
### 2 part (practice)
* react-router usage

### Materials:
- [Lecture (video)](https://youtu.be/YwOkBljMNpc)
- [Slides](https://andre-gl.github.io/talks-react-router/)
- Articles:
    https://reacttraining.com/react-router/web/guides/philosophy
    https://egghead.io/lessons/react-run-the-react-router-v4-examples-with-create-react-app

## React. 6 Lecture. Flux+Redux

Form for questions: https://docs.google.com/document/d/1IZpVZTCegi7rmVXcZpp-rE_Z_UZbWjgrT06qszGFBaU/edit?usp=sharing

### 1 part
* the problem with app state managment in react
* the problem with passing props from root component to leaf components
* what is flux architecture
* what is redux
* immutability
* pure functions
* main redux principles (read-only state, reducer, actions)
* middlewares

### 2 part (practice)
* redux implementation
* redux usage

### Materials:
- [Lecture (video)](https://youtu.be/s060_ZWWhVE)
- [Slides](https://slides.com/artemsinicyn/deck)
- [Code Examples](https://github.com/cardamo/redux-with-tests-example-4rss)
- Articles:
    https://github.com/mobxjs/mobx
    https://github.com/CharlesStover/reactn
    https://github.com/andregardi/use-global-hook#readme
    https://react-redux.js.org/next/api/hooks

## React. 7 Lecture. SSR

Form for questions: https://docs.google.com/document/d/12i8sSn5K8qbDjYmOUYWY1kaii_60C4dm6gZ2Bt5RXho/edit?usp=sharing

### 1 part
* serverside rendering as a way to solve the main problems of SPAs
* why serverside rendering isn't silver bullet
* TBA

### 2 part (practice)
* ssr implementation (live)

### Materials:
- [Lecture (video)](https://youtu.be/4cGApe7DsGY)
- [Slides](https://slides.com/yuliaka71/deck)
- [Code Examples](https://github.com/yuliaHope/ssr-test-example)
- Articles:
    https://blog.logrocket.com/why-you-should-render-react-on-the-server-side-a50507163b79/
    https://ru.reactjs.org/docs/react-dom-server.html
    https://itnext.io/server-side-rendering-with-react-redux-and-react-router-fa5b67d4965e
GitHub

## React. 8 Lecture. Testing

Form for questions: https://docs.google.com/document/d/1yl5g74K3Ohd407PRpG34LoQWGRXl_DSQzbzKmAzHewE/edit?usp=sharing

* Testing react apps
* jest
* enzyme
* TBA

### Materials:
- [Lecture (video)](https://youtu.be/gK5I7bq72Fw)
- [Code Examples](https://github.com/cardamo/redux-with-tests-example-4rss)
