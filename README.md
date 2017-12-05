### NPM, the real Javascript MVP.

with all its quirks and all, the node package manager, is one tool no javascript developer should live without…unless you substituting with **yarn**, which essentially is another package manager.

### NPM, AKA Node Package Manager, AKA ( Mr. I will download the package every bloody time..) , for those who don’t know , can be described as a tool used for managing your javascript project dependencies. 

If we were to describe it, with a programmer’s gibberish :

> “npm installs packages which are essentially libraries know as dependencies to your project which then get stored under a folder , properly labelled **node_modules** .

In really plain english, it helps install and / or remove ( “Manage”) the many libraries utilised during the construction / development of a javascript based project.

### **Now, Why Was The Node Package Manager Created ?**

Well, let me put it this, way…

Without NPM, it would be veeeery inconvienient as regarding utilising code or snippets of code / libraries built by other people to solve specific problems,

NPM makes it easy for javascript developers to share codes that they have used to solve a problem and these shared codes can be reused by other developers to solve problems related to their own applications. The shared codes can also be updated when changes have been to them and other developers can download the updated code for their own projects.

The reusable bits of codes are called modules or packages. A package is a directory with one or more files in it.

### How do i get it onto my system?

\- Go to the link <https://nodejs.org/en/download/> and download the version for your pc and install

\- Run command “**npm –v**” or “**node –v**” to check if installation was successful and see the version of npm and node installed

\- To update installed npm, run “**npm install npm@latest –g**”

### **But Wait Where Does Package.json Come in?**

 package.json is a file that contains metadata about the package. It’s is generated when a particular npm command is initialised. said command also happens to be of the syntax:

**npm Init.**

### **Wait, Commands ?**

Yup, commands…sweet, sweet commands.

Npm has a lot of commands, but typically only very few are used regularly.

**npm init **: running this command creates a package.json file in your project directory.

**npm install \*PackageName***: running this command downloads a package named *PackageName* and stores it to a folder named node_modules in your project directory.

**npm install \*PackageName*  — save**: running this command downloads a package named *PackageName* and updates the package.json file with the name of the newly installed package.

**npm install \*PackageName* -g**: running this command installs the package to a directory on your system rather than the project directory making it available to any project in need of it.

**npm install** : running this command would do a fresh install of all the packages listed in your package.json file to your project directory.

**npm uninstall \*PackageName***: clearly..running this command..uninstalls the package from your project.

**npm uninstall \*PackageName* -g**: clearly..running this command..uninstalls the package globally..

**npm update**: would try to update all the dependencies listed in your package.json to the most recent version made available by the package creator.

**npm update \*PackageName***: would try to update the package listed in your package.json to the most recent version made available by the package creator.

and so many more…so…many many more..checkout <https://docs.npmjs.com/cli/start>.

### So, Where exactly do i execute this commands? 

A nice little place called the your **terminal** or if you a windows person, **command prompt.**

well, you actually type in the commands into the command line interface, AKA the **CLI**.

### **Yaay, now you know NPM**

And that’s pretty much a it, a decent introduction to NPM, by** The React Team, Planet NEST.**

### 