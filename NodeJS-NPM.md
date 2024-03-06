Learning Resouece : https://heynode.com/tutorial/what-packagejson/#:%7E:text=json%20file%20is%20the%20heart,entry%20point%20to%20our%20package


# What is NPM?
NPM stands for Node Package Manager. NPM is a Command line utility to install Node.js packages, perform version management and dependency management of Node.js packages.

If you install newer version of Node.js (version 0.6.0 or later), the NPM utility is included with it. Check the version of NPM in the command terminal −
 
```command prompt
> npm -v

```
--------------------------------------------------

**```npm install <package name>```** & **```npm init```** are not the same commmands.

**```npm install <package name>```** is used to download a package that's in the NPM repository while npm init is used to initialize a project and creates a package.json file. This file keeps track of libraries installed in the project by adding the installed package's name and version.

If you did not initialize the project and proceeded to run **```npm install <package_name>```**, npm will install the package, create the package.json file and add the recently-added package to it.
