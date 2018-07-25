# Create a React App

## Description
We will be building a new React App from scratch using ```create-react-app```.

We will first go through the initial setup, and we will then build a ```component``` that will be displayed on our browser.

## Instructions

### Setup
1. Change directory into the wyncode folder.
2. use ```create-react-app``` to build a new React app named ```react-implementation-1```
3. Change directory into the newly created app directory.
4. Delete everything all files in the ```src``` folder.
5. Create an ```index.js``` file in the ```src``` folder

### Create your first component.

1. Create a ```components``` folder in the ```react-implementation-1``` directory.
2. Create an ```app.js``` file inside this directory.
3. In ```app.js``` import ```react``` so that we can build a component
4. Create a ```class``` named App that extends from ```React.Component```
5. Make this class ```render``` the a ```<ul>``` with 3 ```<li>``` the contents of each ```<li>``` is up to you.
6. You will then need to export this file so that it can be imported by your ```index.js``` file. (We haven't done this in class, so raise your hand when you get here).
7. In the ```index.js``` file you will import the ```app.js``` component, ```react``` and ```react-dom```.
8. You will use the ```ReactDOM.render()``` function to render an instance of the ```app``` component after an element with ```id``` of ```root```

