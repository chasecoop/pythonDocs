---
title: Welcome to Python for Visual Studio Code
---


Python for Visual Studio Code is an extension for Visual Studio which aims at providing you with the best python development environment and experience possible. The extension is built for the Visual Studio Code IDE that is built from the ground up using Open Source technologies such as NodeJs.

![Preview](https://raw.githubusercontent.com/DonJayamanne/pythonVSCode/master/images/general.gif)  

![Debug](https://raw.githubusercontent.com/DonJayamanne/pythonVSCode/master/images/standardDebugging.gif)

## Open Source and Cross Platform
The extension along with the IDE is both open source and runs on multiple platforms such as Windows, Mac and Linux. Both the Python extension and Visual Studio Code are built using open source technologies such as NodeJs.

## Works out of the box
Once installed, the extension works out of the box with absolutely no configuration. This is made possible by using the default Python interpreter available in the current PATH variable on the operating system.

If necessary, the python interpreter being used by the extension could be changed to point to a specific version of the interpreter (or one that is in a specific virtual environment). This is made possible by altering the following setting in the User or Workspace settings file:
```json
"python.pythonPath" : "<fully qualified path to the python interpreter>"
```    

    
## Features
### Features built into Visual Studio Code
- Integrated support for git
- Split editors
- Diff viewers
- Integrated terminals
- Themes
- Excellent support for other languages html, javascript, typescript, nodejs, go, css, etc

### Virtual Environments
Python virtual environments are completely supported.

### Rich Intellisense (code completion)
The extension provides a very rich set of intellisense and code completion capabilities. This significantly reduces the development effort by removing the guess work from the equation. Intellisense (code completion) works out of the box with no additional configuration. However, this can be fined tuned if necessary.

### Code Navigation and the like
The extension integrates with most if not all of the code navigation capabilities exposed by the Visual Studio Code IDE. What this means to the end user is simple, features such as Go to Definition, Go to Symbol, Find all References, hover over a symbol to view the documentation, etc. are available to the user through the IDE via standard commands and interfaces.
This alone feature alone saves development time and effort with improved code navigation.

### Linting (Code analysis)
The extension utilizes some of the best and most popular python linters in order to analyze the source code and provide feedback to the user. Popular linters such as Pylint, Flake8, pydocstyle, and the like are used. As a user you could either use all of them or just one or none. Users have the ability to fine tune each linter placing relevant configuration files in the project directory.

### Code formatting
Code formatting ensures your code meets certain standards of coding styles. This capability is provided by using either one of Yapf or AutoPep8 library. Using this feature you can be assured your code meets some of the best known standards in python coding (format) styles.

### Debugging
The debugging experience provided is unparalleled. You could debug almost any type of application, web and console applications, local and remote applications (yes remote debugging too). The debugger provides a rich set of debugging capabilities such as:

- Multi-threaded debugging
- Local variables and arguments
- Watch window and stack trace
- Conditional breakpoints
- Evaluating expressions and more

### Unittests
- Running all, failed or specific tests
- Viewing test results
- Debugging unittests
- Support for unittests, pytest and nose

### Refactoring
- Renaming
- Extracting variables
- Extracting methods 
- Sorting imports 

### Data Science (Jupyter)
- Executing line, selected code or cells against a kernel
- Grouping blocks of code into cells in the editor
- Managing kernels (restart, interrupt, shutdown or selecting another kernel)
- Viewing results in Visual Studio Code (interactive graphs, LaTeX, SVG, images, etc)

### Miscellaneous features that make this a great Python development IDE
- Auto-indenting as you type
- Code Snippets
- Executing selected code or a file in a python terminal
- Local help file

## Contributions and Suggestions
If you have an idea, we’d love to hear about it, you can add them here.

If you think you can build it, then by all means fork the repo, make the changes and create a pull request.

## License
[MIT](https://raw.githubusercontent.com/DonJayamanne/pythonVSCode/master/LICENSE)