># Setting up the React Environmment
* Keeping the process very simple, as its most fearful to setup but fear now its very simple. Lets proceed...

### 1. Install Node and NPM
1. Go to the Official website of Node - ```https://nodejs.org/en/```
2. Go to Downloads - ```https://nodejs.org/en/download/```
3. Download the LTS version as this version is more stable than the current version.
4. After installation is compl.
4. After installation is complete, Click on Next to follow the instructions.
* Note : To check if you have installation is successful - Run the command :
```js
node -v
npm -v
```
* You must see the versions which denotes it is successful.
* NPM is installed alongwith Node so no worries!

### 2. Integrated Development Environment - Visual Studio Code
* There are many IDE available however, Mostly used is VS Code due to following reasons :
* Code refactoring & debugging
* Easy extensibility and customizability
* Variety of plugins and themes
* Integrated Terminal (Command Line Interface).
   
3. After installation is complete, Click on Next to follow the instructions.
* Note : To check if you have installation is successful - Type :
```js
node -v
npm -v
```
* You must see the versions which denotes it is successful.
* NPM is installed alongwith Node so no worries

### 3. Create a React boilerplate application
   
1. Open Visual Studio Code
2. Open terminal - as we are going to use VS Code's inbuilt terminal
3. Run the command - ```npx create-react-app my-app``` - This command creates the app name my-app.
4. Go inside your app by - ```cd my-app```
5. Start your application by ```npm start```
* Your app would start in your default browser at ```http://localhost:3000/```

### Congratulations! Your app is ready.


---


># Folders Explanation of React App
* We started our application in last step. Now you must be wondering what these actually contain and for very beginners it might look a lot! Just remember - Coding demands Patience!
* Now we will see what these folders actually aim at :
1. package.json
* This is the ```Most important file of the project```.
* It contains entire information of the application.
* It contains information like package name, version, commands etc.
* When comes to sharing of project this is the main file to be shared.
* If by any chance you deleted your node_modules folder Or If you are running someone else's project and want to install the packages just run the command ```npm install``` - Which takes all the package versions from this file and install accordingly.
 
### 2. package-lock.json
* In simple words, it contains details of package.json
* Its main content include history and versions of packages and their dependencies.
* It locks dependencies to a specific version and hence got the name!
 
### 3. .gitignore
* When we upload project to the git - there are some heavy files which have to be ignored to upload and these details we add here.
* Most commonly ignored is node_modules folder, as package.json is sufficient for it and this being very heavy with packages should be ignored.
 
### 4. src
* This folder contains all the work of react.
* For a developer this is their desk!
 
### 5. App.js
* This file contains the starting code of the project.
* We will go in detail in upcoming articles.
 
### 6. App.test
* This file contains unit test cases.
 
### 7. index.js###
* This file is the ```Entry point of React```
 
### 8. reportWebVitals.js
* This file is important for Performance Reports
 
### 9. setupTest.js
* All test cases are set up here.
 
### 10. public
* This folder contains index.html file - which has all the HTML details and most importantly hold #id (We will discuss this in detail later)
 
### 11. manifest.json
* This is a meta file.
* It includes icons, display details etc.
* This is primarily used in Corresive web apps.
 
### 12. robots.txt
* This is to prevent the search engines and bots to crawl up to the website.
* It avoids overloading of requests.
 
### 13. Build files
* This folder is useful when we go for uploading our website.
* It contains all the information required to install and start our application.
 
### 14. node_modules
* All packages and dependencies get stored here.
* Their details are stored in package.json file.
* On npm install, node_modules folder gets generated.


># Extra Shot : Interview Questions
1. How can you create a CRA app in react?
* Answer : CRA App is Create React App in React.
* It is created with command:
``` npx create-react-app myapp```
* myapp here is the project name which can be anything
* Project name is conventionally written in small caps

2. What is the difference between npx and npm?
* Answer - Basically npx is used when package.json is not there, in case of creating a new project. npm is used when package.json file is already present.
* npm is used to download JavaScript packages from NPM, whereas npx is used to execute JavaScript packages.

3. Why node_modules is not pushed in GIT?
* Answer - Reason being very heavy. Already explained above
4. How does other person get node_modules if not pushed?
* Answer - Using npm install command. Already explained in detail above.
5. What is the most important file in a react app?
* Answered above
6. What is the entry point of react code?
* Answered above

7. Do you need both package.json and package-lock.json?
* Answer - NO. Comment below to know more!

8. Can only package.json be sufficient?
* Answer - YES. Comment below to know more!

9. Can only package-lock.json be sufficient?
* Answer - NO. Comment below to know more!

10. Can you use any other command to start the application in place of npm start?
* Answer - YES.
* We will have to change the script start command in package.json file
```js
"scripts": {
    "start": "react-scripts start",
    ...
    }
```
* If I write ``` "start": "react-scripts begin"``` in place of ```"start": "react-scripts start"```.
* I can now start the application using ```npm rum begin``` inplace of ```npm start```.

Happy Learning!

- Article by Ayushi Jain
