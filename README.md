Front-End Projects Gateway
====================================

Overview
------------------------------------
A Gateway to all my front-end practice projects repositories.

The description shown here for each of them is very brief, so do not hesitate to go read their own README files.

Projects list
------------------------------------
- ***Yugi-Calculator-MAX***
  - An multi-purpose app to assist Yu-Gi-Oh! duelists, taken to the max!
  - [Working example](https://ycm.netlify.app/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/Yugi-Calculator-Max)
  
- ***RNMC Colors***
  - A Color Palette generator web app to save your customized palettes and copy color codes in diverse formats.
  - [Working example](https://renzomurinacadierno.github.io/React-RNMCRainbow/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCColors)
  
- ***RNMC Burgers***
  - A web app to customize and order your personal favorite burgers.
  - [Working example](https://rnmcburgers.web.app/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCBurgers)
  
- ***RNMC Clothes***
  - A fully functional e-commerce web app powered by React.
  - [Working example](https://rnmcclothes.herokuapp.com/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCClothes)

- ***RNMC Pokedex***
  - A Pokemon finder web app created to teach React's basics.
  - [Working example](https://rnmc-react-pokedex.netlify.app/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/React-Pokedex)

- ***Gatsby.js Test Blog***
  - A simple blog app made with GatsbyJS and hosted in Netlify.
  - [Working example](https://rnmcgatsbyblog.netlify.com/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/gatsby-test-blog)
  
- ***RNMC React Blog***
  - A simple blog app made with react from scratch.
  - [Working example](https://rnmcreactblog.web.app/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCReactBlog)
  
- ***Vanilla Connect 4***
  - A very basic "Connect 4" game made with vanilla HTML, CSS and JS.
  - [Github repository](https://github.com/RenzoMurinaCadierno/VanillaConnect4)
  
  
**Yugi-Calculator-MAX**
------------------------------------
An multi-purpose app to assist Yu-Gi-Oh! duelists, taken to the max!

  - [Working example](https://ycm.netlify.app/)
  - [Github repository](https://github.com/RenzoMurinaCadierno/Yugi-Calculator-Max)
  
Yugi Calculator MAX (YCM) is an app made by a fan for fans. It includes some helpful utilities created to assist Yu-Gi-Oh! duelists in or off game:

  - Duel calculator
  - Logging
  - Card searching (with their prices in the market)
  - Deck building (with hand/draw testing capabilities)
  -Configuration menu (to customize the app)

Besides libraries mentioned in "Acknowledgments" section inside the app, YCM was completely built from scratch. Almost all hooks used here, as well as state management, component logic and styling, mediaqueries and the likes, were home-made.
  

**RNMC Colors**
------------------------------------
A Color Palette generator web app to save your customized palettes and copy color codes in diverse formats.

- [Working example](https://renzomurinacadierno.github.io/React-RNMCRainbow/)
- [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCColors)
  
A web app that allows you to create your own custom color palettes, name it and the colors inside of it. You can view it at any time, dynamically vary each color's luminosity and select HEX/RGB/RGBA formats to copy it to clipboard. Colors can be re-ordered in creation-mode by drag-and-dropping them, you can customize both colors and palette's names, delete and add new ones as you please.

Material UI was the framework responsible for the styling, which I used to enhance breakpoints for each device size suggested there. ChromaJS and react-color libraries made working with colors way easier, and react-copy-to-clipboard aided with that functionality specified on its name. Array-move and react-sortable-hoc were utilized to add drag-and-drop mechanics to palette creation, and emoji-mart for the standard emoji picker solution add a finishing touch to palette names.

**RNMC Burgers**
------------------------------------
A web app to customize and order your personal favorite burgers.

- [Working example](https://rnmcburgers.web.app/)
- [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCBurgers)
  
A simple burger-customization web app, where you can add or remove ingredients on the fly. The burger is re-created instantly as you do so, price gets updated in real time and you can log in to complete a form to order it. All burgers you order are stored in Firebase and you can retrieve them with the given option available in the navigation bar.

User authentication and session persistance is handled. You can log in, close the browser and reopen it, and the app should still reckon it is you. LocalStorage is used for session persistance, and timeout is checked each time the App renders. If session expires, a logout action is automatically dispatched.

Create-react-app was used to initialize the project, but the project involves several libraries. Redux, Redux Sagas, React-Router, Hooks, Axios, PropTypes, React Lazy and Suspense, and some other libraries and utilities made the app as a whole.

RNMC Clothes
------------------------------------
A fully functional e-commerce web app powered by React.

- [Working example](https://rnmcclothes.herokuapp.com/)
- [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCClothes)

Nothing but functional e-commerce app, an Outlet one to be precise. You can browse each category and check for the items there, add items to your cart and check out. Payment simulation is available if you want to test it.

User authentication and session persistance is handled. You can log in, close the browser and reopen it, and the app should still reckon it is you. Speaking of which, you can sign up, and log in with either your signed up email and password or with your Google account. Firebase handles both.

This is one of the most complete and functional apps I have uploaded up to now. Create-react-app was used to initialize the project, but the magic wouldn't have sparkled without the whole ecosystem that surrounds it. Redux, Redux Persist, Redux Sagas, React-Router, React Lazy and Suspense, ErrorBoundary, Firebase Firestore, NodeJS, Express, Styled Components, Stripe payments and some other libraries and utilities made what you see here possible.

It also works offline, as it is also a Progressive Web App. Open the webpage where the site is hosted with a mobile device and it will ask you if you wish to download it. Or, open it from a laptop/PC using a compatible browser (preferably Google Chrome), and download it from that browser's menu.

RNMC Clothes
------------------------------------
A Pokemon finder web app created to teach React's basics.

- [Working example](https://rnmc-react-pokedex.netlify.app/)
- [Github repository](https://github.com/RenzoMurinaCadierno/React-Pokedex)

A simple web app created in a session of some hours used to teach the basics and a little more to some people willing to learn React's ecosystem. 

No class-based components were used here, everything is leveraged with functions and hooks for the sake of simplicity. useState, useEffect and useContext were implemented, as well as two custom hooks. Hooks lifecycles using dependencies and cleanup were dealt with too. Topics covered also included React-router-dom, React-transition-group, Lazy loading with Suspense, fetch requests, CSS modules, Context API and controlled inputs.
  
Gatsby.js Test Blog
------------------------------------
A blog app made with GatsbyJS and hosted in Netlify.

- [Working example](https://rnmcgatsbyblog.netlify.com/)
- [Github repository](https://github.com/RenzoMurinaCadierno/gatsby-test-blog)

This project was made possible due to the curiosity of learning at least the basics on Gatsby and to keep on practising GraphQL. It is just a simple blog where you can post and read posts. Only the admin can upload blog posts, there is no signup or signin system as I wanted to keep it as simple as it could be.

RNMC React Blog
------------------------------------
A simple blog app made with react from scratch.

- [Working example](https://rnmcreactblog.web.app/)
- [Github repository](https://github.com/RenzoMurinaCadierno/React-RNMCReactBlog)

Signup/Login, create/edit/delete your posts, view other people's posts via their URL. Nothing much besides that.

Even though I know the most commonly used module -and automatic way of creating the scaffolding of a react app- is *create-react-app*, it is always better to know how to do anything from the ground up, and that is why this project is here and done the way it is.

[Parcel.js](https://parceljs.org/) was my bundler instead of Webpack, which I would normally use. I chose [Ant design](https://ant.design/) as a styling framework instead of Bootstrap, and [Reach router](https://reach.tech/router) instead of react-router-dom. Do not take me wrong, though. Each mentioned framework/module is awesome and certainly gets its job done, but since I was to build an app from the bare basics, I might as well try some building materials that are new to me too. Why not?

Vanilla Connect 4
------------------------------------
- [Github repository](https://github.com/RenzoMurinaCadierno/VanillaConnect4)

A basic Connect 4 game made with vanilla HTML, CSS and JS.

Place all files inside the same folder and launch the HTML, the game should be automatically playable.

Click on the empty circles to drop the chips. The first one to align 4 diagonally, vertically or horizontally, wins. You can restart the game at any time by refresing the broswer.
