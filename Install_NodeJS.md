# What is Node.js?
Node.js is a powerful JavaScript runtime environment, built on Google Chrome's V8 JavaScript Engine. Node.js is open-source and cross platform, widely used by thousands of developers around the world to develop I/O intensive web applications like video streaming sites, single-page applications, and other web applications.

Contrary to a perception, Node.js is not a programming language like Python, Java or C/C++. Node.js is a runtime, similar to Java virtual machine, that converts JavaScript code into machine code.

With Node.js, it is possible to use JavaScript as a backend. With JavaScript already being a popular choice for frontend development, application development around MERN (MongoDB, Express, React and Node.js.) and MEAN (MongoDB, Express, Angular and Node.js) stacks is being increasingly employed by developers.

----------------------------------
Node.js is a server-side runtime environment built on Google Chrome's JavaScript Engine (V8 Engine). Node.js is a cross-platform (run on Windows, Linux, Unix, macOS, and more), open-source, back-end JavaScript runtime environment, that executes JavaScript code outside a web browser.


# Why Learn Node.js?
Node.js is used for server-side programming with JavaScript. Hence, you can use a single programming language (JavaScript) for both front-end and back-end development.

Node.js implements asynchronous execution of tasks in a single thread with async and await technique. This makes aNode.js application significantly faster than multi-threaded applications.

Node.js is being used to build command line applications, web applications, real-time chat applications, REST APIs etc.
   
# How to check Node.JS in Install in your machine ?
To check node.JS is installed in your machine. Type **node** or **node -v** in command prompt and hit the enter key. It will print node verson in command prompt as showen below.

  ![Screenshot](https://github.com/ladpriteshkumar/Learn-NodeJS/blob/e122d6f4f4c75feab576bb5e784ad28929c4a53a/Images/node%20and%20node_v%20command.png)

If node.Js is not installed then it will print the message as showen below in command prompt.
 
  ![Screenshot](/Images/node_and_node-v_command_node_not_install.png)

# How to Install Node.js?
Installation of Node.js is very easy. For Windows users, the official downloads page of Node.js (https://nodejs.org/en/download) hosts a installer package. All you need to do it download and run the installation wizard.

using **winget** (windows OS)<br> 
You can also use winget command to install nodeJS. Simply open open command prompt and execute below command.

```command prompt
 > winget install nodeJS
```
To uninstall nodeJS using winget command. Simply open comand prompt and execute below command.

```command prompt
 > winget uninstall nodeJS
```

# Getting Started With Javascript and NodeJS 
To run your JavaScript code using nodeJS. first need to create index.js file in system directrory (Ex : C:\WorkPlace\ProjectName\index.js ) and write some javascript statement in it. as showen below.


```JavaScript
//Fie: index.js

console.log("First JavaScript Statement using nodeJS")

```

Now open cmd terminal and navigate to the directory where index.js file is located.

```Command Propmt
 > cd C:\WorkPlace\ProjectName
```

to Execute code written in index.js file, execute **```node .```** in cmd terminal. alternative you can also use **```node index.js```** to execute code written in index.js file.<br> 

```command Prompt
> cd C:\WorkPlace\ProjectName>Node .
//OR
> cd C:\WorkPlace\ProjectName>Node index.js
```

**index.js** is the default file name for ```node .``` command. if you have file name different then index.js then ```node .``` will not work and it throw an error. you have have to use ```node fileName.js``` to execute code written in fileName.js file.



**index.js** is the default entry point of  your node application if you don't define in **package.json** file using **"main"** key or you don't have **package.json** file in you node project root directory.
```JSON
//File: package.json
{
   "main": "entrypointfilename.js"
}
```

you can execute entry point of your application using ```node .``` command
