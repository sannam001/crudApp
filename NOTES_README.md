NodeJs:
    It used to run the js code in the system
    We can use this for creating a back end server, just like tomcat server.
    When we install nodejs software we will also get npm with it.

NPM: Node package manager

What is NPM ?
    It is a set of js files bundled together for achieving certain functionality and published in the 
    NPM. NPM is online repository for publishing open - source Node.Js projects, and command line utility for interacting with that repository
    for package dependency mgmt, package installation and package version management.
    //TODO : Revist the below statement after working with few modules
    Simply NPM consists of different modules, and those modules are having  different written logics called functions() we can use them directly by importing the dependencies. 

How to check version of NPM & node ?
    npm --version -- This code will dispaly the version of it or will display whether it is installed in it or not
     node --version -->>> displays version.

Where does NPM save the reference of dependent modules/packages that are used in the project?
   <strong> It will save in "package.json". Package.Json has all the details of installed dependencies.</strong>

How do we add package.json to our project ?
<p> npm init </p> Creates package.json file  
<p>Ideally the above command we will  run only if the project is started from scratch</p>

What is command for install the dependencies ?
    <p><code>npm i <name of the package> or npm install <name of the package></code></p>
    <p><code> NPM i </code> All packages from NPM will be installed in this repository.</p>
    <P><code> NPM install <name of the package> </code> It will install the package that is given in the code.

What is the pre-requisite for executing above command ?
    We have to ensure that "package.json" file is exists in that particular project folder or not. 
   Pre-requisite for executing above commands is <code>NPM init </code> it will install package.json file. 

   <code>NPM init </code> ----> This code is for installing the package.json file 
   <code>NPM i </code> ---->>> Installs all the packages in the package.json file and create a new folder called Node module folder
   <code>NPM i <Modulename></code>  ----->>>>> Installs  the module given in the command
   <code>NPM <modulename> --save-dev</code> ------->>>>> Installs the dev dependencies
   <code>NPM run <Script module keys></code> ------->>>  Installs the predefined functions or reusable code 
