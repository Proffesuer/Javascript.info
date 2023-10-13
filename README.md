These are sample practicles and notes taken during my refresher course on javascript.info
___________________________________________________________________________
#Introduction
_______________________________
Javascript was initially called livescript.It was initially created to make web pages live. can either be executed in any server or browser today

#what can javascript Do?

    -->Add new HTML to the page, change the existing content, modify styles.
    -->React to user actions, run on mouse clicks, pointer movements, key presses.
    -->Send requests over the network to remote servers, download and upload files (so-called AJAX and COMET technologies).
    -->Get and set cookies, ask questions to the visitor, show messages.
    -->Remember the data on the client-side (“local storage”).

    #What Makes Javascript unique
    -->Full integration with HTML/CSS.
    -->Simple things are done simply.
    -->Supported by all major browsers and enabled by defa

#Languages “over” JavaScript

Modern tools make the transpilation very fast and transparent, actually allowing developers to code in another language and auto-converting it “under the hood”.

Examples of such languages:

    -CoffeeScript- -->is “syntactic sugar” for JavaScript. It introduces shorter syntax, allowing us to write clearer and more precise code. Usually, Ruby devs like it.
    TypeScript-->is concentrated on adding “strict data typing” to simplify the development and support of complex systems. It is developed by Microsoft.
    Flow also adds data typing, but in a different way. Developed by Facebook.
    Dart -->is a standalone language that has its own engine that runs in non-browser environments (like mobile apps), but also can be transpiled to JavaScript. Developed by Google.
    Brython -->is a Python transpiler to JavaScript that enables the writing of applications in pure Python without JavaScript.
    Kotlin -->is a modern, concise and safe programming language that can target the browser or Node.
#Summary

    --JavaScript was initially created as a browser-only language, but it is now used in many other environments as well.
    --Today, JavaScript has a unique position as the most widely-adopted browser language, fully integrated with HTML/CSS.
    -- There are many languages that get “transpiled” to JavaScript and provide certain features. It is recommended to take a look at them, at least briefly, after mastering JavaScript.

#IDE
     An IDE loads the project (which can be many files), allows navigation between files, provides autocompletion based on the whole project (not just the open file), and integrates with a version management system (like git), a testing environment, and other “project-level” stuff.

     If you haven’t selected an IDE yet, consider the following options:

    --Visual Studio Code (cross-platform, free).
    --WebStorm (cross-platform, paid).
#Developer console

     Code is prone to errors. You will quite likely make errors… Oh, what am I talking about? You are absolutely going to make errors, at least if you’re a human, not a robot.

      But in the browser, users don’t see errors by default. So, if something goes wrong in the script, we won’t see what’s broken and can’t fix it.

      To see errors and get a lot of other useful information about scripts, “developer tools” have been embedded in browsers.

     
#JavaScript Fundamentals
check on the html files to see the practicles on the fundamentals
#Use strict 
     use strict to run your script code in a modern way
#Variables
  A variable is a named storage. it is initialized by using the word let.
  use the word let to initialize variables
  example 
  let message;
  #Data types 
  Javascript variables can keep more than one data type
  There are different types of data types like string and numbers 
  
