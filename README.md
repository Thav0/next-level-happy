<h3 align="center">
  Next Week #3 Rocketseat - Happy
</h3>

## :rocket: About the project
<p>
This project is about an app to connect people, to they know that there are orphanages nearby, to visit, how it works and have experience visiting people on orphanages
</p>

<p align="center">
  <img alt="Mockup devices" src="https://i.imgur.com/hdh4xxt.png" width="100%">
</p>

<b>Main knowledge acquired in this project:</b>
- ReactJS
- React Native
- Typescript
  - Typescript is a superset, we can call it a language, it's a javascript with super powers
  - Why should we use typescript?
    - When working in a group, it helps us a lot to know what a particular function will receive or send, as it improves the editor's IntelliSense, allowing to determine the properties of some function or object
- How to use Maps like Google and Leaflet


## :airplane: NodeJS

- Insomnia to test API
- Express
  - Controllers
- Queries with typeorm
- Axios (Promise based HTTP client for the browser)
- How to use CORS (Security Policy Middleware)
- Migrations / Seed

Libs used:
- Typeorm
- Cors (cross-origin)
- Express (micro-framework to build routes)
- Multer (Image upload)
- Yup -> Form validation
- Sqlite3

## :helicopter: ReactJs

- How to choose a technology before start a project
    - Analyse what the market is looking for
    - Check the community e ecosystem around those technologies
    - Who is behind the development
    - Which companies are using the technologies
    - Which cases can we apply it
- Differences between tradicional way and SPA (Single page application)
- React Concepts
    - Components
        - JS Functions
            - Return HTML
    - Props
        - Custom values between components
    - State
        - Source of Data
    - Declarative
    - Virtual DOM
        - React find the best way to re-render the DOM using Virtual DOM
    - Unidirectional Dataflow
- React CLI
- Folder structure
- ES6 functions
- Flexbox
- Interact with maps

## :steam_locomotive: React Native

- Tradicional way of developing for Mobile (Objective-C Swift) | (Java Kotlin Android) VS React Native
- How to use EXPO
    - Without expo we need to install Android Studio and Xcode to get SDKs
    - We can test the app inside expo
    - We can access all libraries needed to develop for mobile
- Differences between ReactJS and React Native
- No semantic Tag
- Types of mobile navigation
- How to style elements
- How to use google maps
- Get user current location using mobile GPS permission
- DeepLinking (Whatsapp / Mail)

### **How to use it**

## Server
cd /server

```
yarn (to install dependencies)

yarn typeorm migration:run (To run all migrations at once)

yarn dev
```

## Web
cd /web

```
yarn (to install dependencies)

yarn start

http://localhost:3000/
```

## Mobile
cd /mobile

```
Search for expo on GooglePlay / Apple Store and install it

yarn (to install dependencies)

yarn start

Scan QRCode with expo
```
