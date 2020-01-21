# Modern-React
Links to articles to help developers with writing modern React (web) apps. Also includes links to modern Javascript (ES2016-ES2020).

NOTE: Currently these are links I've added to Pocket over the last 12 months, many of which I haven't read. I'm creating this page to help others, and to nudge me to start reading them. As I start reading through these, I will remove the articles that aren't too helpful, so that this page evolves into a list of **vetted** links. 

NOTE 2: Some of these links may require a Medium membership. If you find a link that requires a Medium membership, but the article is also available for free (because it was republished on Medium), please let me know and I'll update the link.

Future: I will consider adding TypeScript links.

### React
* [Architecture & Design](#architecture-and-design)
* [Authentication](#authentication)
* [Context](#context)
* [CSS-in-JS](#css-in-js)
* [Data Fetching](#data-fetching)
* [Dev Tools](#dev-tools)
* [Forms](#forms)
* [Hooks](#hooks)
* [Hooks - Custom](#hooks---custom)
* [Performance](#performance)
* [Portals](#portals)
* [PWA](#pwa)
* [Redux](#redux)
* [Refs](#refs)
* [Routing](#routing)
* [Storybook](#storybook)
* [Styled Components](#styled-components)
* [Suspense & Concurrent](#suspense)
* [Testing](#testing)

### Javascript
* [Symbols](#symbols)


## React

### Architecture and Design
* [Sharing React Components: From Atoms and Molecules to Pages](https://blog.bitsrc.io/sharing-react-components-from-atoms-and-molecules-to-pages-2d0d722b1dba)
* [Domain Driven Design and Functional Pure UI Components](https://dev.to/kmruiz/domain-driven-design-and-functional-pure-ui-components-29a7)
* [Understanding Compound Components in React](https://blog.bitsrc.io/understanding-compound-components-in-react-23c4b84535b5)
* [14 Beneficial Tips to Write Cleaner Code in React Apps](https://jsmanifest.com/14-beneficial-coding-tips-to-write-clean-code-in-react/)
* [Some Best Practices for Building a React App With Hooks](https://medium.com/better-programming/some-best-practices-for-building-a-react-app-with-hooks-d6157494f5c1)
* [Domain-Driven Design With React](https://css-tricks.com/domain-driven-design-with-react/)
* [Simple React Patterns](http://lucasmreis.github.io/blog/simple-react-patterns/)
* [The Benefits of Orthogonal React Components](https://dmitripavlutin.com/orthogonal-react-components/)
* [A deep dive into React Fiber internals](https://blog.logrocket.com/deep-dive-into-react-fiber-internals/)
* [Making stupid React smart in re-rendering](https://medium.com/swlh/making-stupid-react-smart-in-re-rendering-5f04b5bab327)
* [8 Useful Tricks for React Apps You Should Know](https://medium.com/better-programming/8-useful-tricks-for-react-apps-you-should-know-a15c2678c846)
* [Don't Sync State. Derive It!](https://kentcdodds.com/blog/dont-sync-state-derive-it)
* [Leaky Components](https://medium.com/charisol-community/leaky-components-446dec290cb4)

### Authentication
* [How to Add Authenticated Routes to Your React App](https://medium.com/javascript-in-plain-english/how-to-add-authenticated-routes-to-your-react-app-f496ff266533)

### Context
* [Redux VS React Context: Which one should you choose?](https://www.ibrahima-ndaw.com/blog/redux-vs-react-context-which-one-should-you-choose/)
* [The Problem with React's Context API](https://leewarrick.com/blog/the-problem-with-context/)
* [Manage Global State with Context API and Hooks](https://react.christmas/2019/7)
* [Learn React Context in 5 Minutes - A Beginner's Tutorial](https://www.freecodecamp.org/news/react-context-in-5-minutes/)
* [React Context Patterns with useContext Hook](https://medium.com/javascript-in-plain-english/react-context-patterns-with-usecontext-hook-62085b90c7eb)

### CSS-in-JS
* [Understanding CSS-in-JS](https://www.telerik.com/blogs/understanding-css-in-js)

### Data Fetching
* [React Adaptive Loading Hooks & Utilities](https://github.com/GoogleChromeLabs/react-adaptive-hooks/blob/master/README.md)

### Dev Tools
* [Why Did You Render](https://github.com/welldone-software/why-did-you-render)
* [Adding React Fast Refresh to Your Create React App Project](https://dutzi.party/react-fast-refresh/)
* [Profile a React App for Performance](https://kentcdodds.com/blog/profile-a-react-app-for-performance)
* [React Dev Tools - Debug Like a Ninja](https://medium.com/the-thinkmill/react-dev-tools-debug-like-a-ninja-c3a5d09895c6)

### Forms
* [Best Practices for Handling a Form With Multiple Inputs Using React Hooks](https://medium.com/better-programming/best-practices-for-handling-a-form-with-multiple-inputs-using-react-hooks-a0abf9207284)
* [Handling React Forms and Validation with Formik and Yup](https://blog.bitsrc.io/handling-react-forms-and-validation-with-formik-and-yup-dc789fd9e485)

### Hooks
* [Deep dive: How do React hooks really work?](https://www.netlify.com/blog/2019/03/11/deep-dive-how-do-react-hooks-really-work/)
* [How to get previous props/state with React Hooks](https://blog.logrocket.com/how-to-get-previous-props-state-with-react-hooks/)
* [React's useEffect and useRef Explained for Mortals](https://leewarrick.com/blog/react-use-effect-explained/)
* [How to Use the useReducer React Hook to Share Data Between Components](https://medium.com/swlh/how-to-use-the-usereducer-react-hook-to-share-data-between-components-83123c9580a4)
* [Introduction to React.memo, useMemo and useCallback](https://medium.com/shot-code/introduction-to-react-memo-usememo-and-usecallback-ca4a312d19b3)
* [The Wise Guide to React useState() Hook](https://dmitripavlutin.com/react-usestate-hook-guide/)
* Two Part Series: [Frustrations with React Hooks](https://blog.logrocket.com/frustrations-with-react-hooks/), [Solutions to Frustrations With React Hooks](https://blog.logrocket.com/solutions-to-frustrations-with-react-hooks/)
* [What do they mean by memoized callbacks and what does useCallback actually do?](https://lukaszmakuch.pl/post/usecallback)
* [Be Aware of Stale Closures when Using React Hooks](https://dmitripavlutin.com/react-hooks-stale-closures/)
* [When to useLayoutEffect Instead of useEffect](https://daveceddia.com/useeffect-vs-uselayouteffect/)
* [React Hooks: Recipes](https://codeburst.io/react-hooks-recipes-1c18e5984abe)
* [The Power of React Hooks](https://medium.com/better-programming/introduction-to-react-hooks-e0102c038bf1)

### Hooks - Custom
* [useBreakpoint Hook — Get Media Query Breakpoints in React](https://medium.com/better-programming/usebreakpoint-hook-get-media-query-breakpoints-in-react-3f1779b73568)

### Performance
* [10 Ways to Optimize Your React App’s Performance](https://blog.bitsrc.io/10-ways-to-optimize-your-react-apps-performance-e5e437c9abce)
* [Trim the Fat From Your Bundles Using Webpack Analyzer & React Lazy/Suspense](https://itnext.io/trim-the-fat-from-your-bundles-using-webpack-analyzer-react-lazy-suspense)
* [6 tips for better React performance](https://itnext.io/6-tips-for-better-react-performance)
* [A Story of a React Re-Rendering Bug](https://www.eventbrite.com/engineering/a-story-of-a-react-re-rendering-bug/)
* [How to Memoize Components in React](https://medium.com/@rossbulat/how-to-memoize-in-react)
* React Hooks Oops: [React hooks... Oops! Part 1 - Introduction](https://lukaszmakuch.pl/post/react-hooks-oops-part-1-introduction/), [React hooks... Oops! Part 2 - why does my effect run multiple times with the same dependencies?](https://lukaszmakuch.pl/post/react-hooks-oops-part-2-effect-runs-multiple-times-with-the-same-dependencies/), [React hooks... Oops! Part 3 - an effect doesn't run again when its dependencies change](https://lukaszmakuch.pl/post/react-hooks-oops-part-3-an-effect-does-not-run-again-when-its-dependencies-change)
* [Increase your React + Redux Application Performance With the Reselect Library](https://medium.com/better-programming/increase-your-react-redux-application-performance-with-reselect-library)
* [State Colocation will make your React app faster](https://kentcdodds.com/blog/state-colocation-will-make-your-react-app-faster)

### Portals
* [Learn React Portals by example](https://blog.logrocket.com/learn-react-portals-by-example/)

### PWA
* [From create-react-app to PWA](https://blog.logrocket.com/from-create-react-app-to-pwa/)

### Redux
* [Official Redux Style Guide](https://redux.js.org/style-guide/style-guide/)
* [How I reduced the code in my Redux app by using Redux Hooks](https://medium.com/javascript-in-plain-english/how-i-reduced-the-amount-of-code-in-my-redux-app-by-using-redux-hooks)
* [Bridging the Gap between React's useState, useReducer, and Redux](https://leewarrick.com/blog/a-guide-to-usestate-and-usereducer/)
* [Selectors in a Redux World](https://medium.com/top-hat-engineering/selectors-in-a-redux-world)

### Refs
* [A guide to React refs: useRef and createRef](https://blog.logrocket.com/a-guide-to-react-refs/)
* [Cleaning up the DOM with ForwardRef in React](https://blog.logrocket.com/cleaning-up-the-dom-with-forwardref-in-react/)
* [React: Using Refs with the useRef Hook](https://medium.com/@rossbulat/react-using-refs-with-the-useref-hook)

### Routing
* [Everything I Know About UI Routing by Ryan Florence](https://gist.github.com/ryanflorence/f812198561c58aec1326ac800e6ea519)
* [How to restrict your Routes and Links in React.js now with Hooks](https://medium.com/craft-academy/how-to-restrict-your-routes-and-links-in-react-js-now-with-hooks)
* [A Quick Start Guide to Query Strings with React Router](https://spin.atomicobject.com/2019/10/01/a-quick-start-guide-to-query-strings-with-react-router/)

### Storybook
* [Storybook 5.3](https://medium.com/storybookjs/storybook-5-3)
* [Declarative Storybook configuration](https://medium.com/storybookjs/declarative-storybook-configuration)
* [Learn Storybook: Design Systems for Developers](https://www.learnstorybook.com/design-systems-for-developers/)

### Styled Components
* [React. 7 tricks to work with Styled Components](https://medium.com/javascript-in-plain-english/react-7-tricks-to-work-with-styled-components)
* [Styled Components, Styled Systems and How They Work](https://medium.com/rangle-io/styled-components-styled-systems-and-how-they-work)
* [Are You Drowning In A Pile Of Styled React Components?](https://codeburst.io/are-you-drowning-in-a-pile-of-styled-react-components)
* [Building Reusable React UI Components with styled-components](https://blog.bitsrc.io/building-reusable-react-ui-components-with-styled-components-290686648004)

### Suspense
* [Using Suspense with react-query](https://blog.logrocket.com/using-suspense-with-react-query/)
* [Diving Into React Suspense Render-as-You-Fetch for REST APIs](https://medium.com/better-programming/diving-into-react-suspense-render-as-you-fetch-for-rest-apis)
* [Suspense Explained](https://adamrackis.dev/suspense-explained/)
* [How Concurrent React changes the game for data-heavy UI](https://medium.com/@winwardo/how-concurrent-react-changes-the-game-for-data-heavy-ui)

### Testing
* [Behavior-driven React development with Cucumber](https://medium.com/swlh/behavior-driven-react-development-with-cucumber)
* Javascript testing series from wanago.io: [#1. Explaining types of tests. Basics of unit testing with Jest](https://wanago.io/2018/08/27/testing-javascript-tutorial-types-of-tests-of-unit-testing-with-jest/), [#2. Introducing Enzyme and testing React components](https://wanago.io/2018/09/03/javascript-testing-tutorial-part-two-introducing-enzyme-and-testing-react-components/), [#3. Testing props, the mount function and snapshot tests](https://wanago.io/2018/09/10/javascript-testing-tutorial-part-three-testing-props-the-mount-function-and-snapshot-tests/), [#4. Mocking API calls and simulating React components interactions](https://wanago.io/2018/09/17/javascript-testing-tutorial-part-four-mocking-api-calls-and-simulating-react-components-interactions/), [#5. Testing hooks with react-hooks-testing-library and Redux](https://wanago.io/2019/12/16/javascript-testing-5-testing-hooks-with-react-hooks-testing-library-and-redux/), [#6. Introduction to End-to-End testing with Cypress](https://wanago.io/2019/12/30/javascript-testing-introduction-end-to-end-testing-cypress/), [#7. Diving deeper into commands and selectors in Cypress](https://wanago.io/2020/01/06/javascript-testing-commands-and-selectors-in-cypress/), [#8. Integrating Cypress with Cucumber and Gherkin](https://wanago.io/2020/01/13/javascript-testing-cypress-cucumber/)
* [Mocking React hooks when unit testing using Jest](https://www.richardkotze.com/coding/mocking-react-hooks-unit-testing-jest)
* [Testing React Hooks With Enzyme and React Testing Library](https://css-tricks.com/testing-react-hooks-with-enzyme-and-react-testing-library/)
* [Testing Custom React Hooks with Jest](https://www.newline.co/@jamesfulford/testing-custom-react-hooks-with-jest)
* [How to Test React Hooks (The Async Ones)](https://medium.com/flatiron-labs/testing-async-react-hooks)
* [Test React apps with React Testing Library](https://thomlom.dev/test-react-testing-library)
* [How to Create and Test React Custom Hooks](https://blog.bitsrc.io/how-to-create-and-test-react-custom-hooks)
* [How to Write Functional Tests in React (Part 1)](https://blog.echobind.com/writing-functional-tests-with-react-testing-library-part-1)
* [Complete Guide on Unit and Integration Testing of React/Redux Connected Forms](https://blog.bitsrc.io/complete-guide-on-unit-and-integration-testing-of-react-redux-connected-forms-cd6f8476161)

## Javascript

### Symbols
* [Deep dive into ES6 Symbols](https://everyday.codes/javascript/deep-dive-into-es6-symbols/)
