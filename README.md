# Angular

# How to run angular:
-How to install Typescript:
  npm install -g typescript
.
.
.
.


## These are my notes on Angular:


## What is Angular? - basic understanding:
 * -A full-fledged javascript front-end framework used to create single-page applications like gmail.
  
## Why?
 * -Javascript is the most commonly used client-side scripting language.
    -It's written into HTML docs. enabling interactions with webpages.
 * *-Is javascript ideal? - No, BUT:
   * -A variety of frameworks and libraries, designed to help, helps bring in structure and consistency as well as scalability and maintainability.

## What is Angular? - Descriptive understanding:
*  -It's an open source javascript framework written completely in Typescript.
*  -It was primarily aimed to develop single page applications and is maintained by Google angular.
*  -It provides a few advantages while also providing a standard structure for developers.
*  -It uses HTML's Syntax to express application components clearly
*  -It is designed for web, desktop, and mobile platforms.
*  *-**Single page applications**: Applications that get loaded just once
  
## Features of Angular:
 * -DOM - Document Object Model
 *   -Treats an XML or HTML document as a tree structure in which each node is an object representing a part of the document.
 *   -Angular uses regular DOM. This will update the entire tree structure of HTML tags until it reaches the data to be updated.
 *   -**Consider about 100's of updates on the same HTML page and the HTML block is replaced for each request 
    
 * -Typescript: TS + NPM
 *   -Angular is written in Typescript. It is a superset of Javascript and offers excellent consistency.
 *   -Typescript is installed as an NPM package, and thus can be installed with the following command:
 *      -npm install -g typescript
 *   -Typescript defines a set of types to Javascript which helps you write Javascript that is easier to understand.
 *   -All the typescript code compiles down to basic Javascript that can run smoothly on any platform.
 *   -Typescript is not mandatory for developing angular applications but is highly recommended because:
       * -It offers better syntactic structure
       * -Makes the code easier to understand and maintain
        
        
## Data Binding:
*  -Allows an internet user to manipulate webpage elements using a web browser
*  -It is used for webpages that contain interactive components such as forms, calculators, tutorials, and games
*  -Mainly employs dynamic HTML and does not require complex scripting or programming
*  -Inceremental display of a webpage makes data binding extremely convenient when webpages contain large amounts of data
  * -When it comes to Angular, it uses **two-way data binding** so any changes meeting the UI element is reflected in the corresponding model state and conversely any changes        made in the model state are reflected onto the UI state. This allows the framework to connect the DOM to the model via the controller.
  
## Testing:
*  -Angular uses **Jasmine** to run various tests.
*  -The Jasmine framework allows various functionalities to write different kinds of test cases.
*  -**Karma** is the task-runner for the tests:
     * -Uses a configuration file to set the startup reporters and testing framework. 
      
# **Architecture of Angular**

* **MVC** - Model View Controller
*  Angular is a full-fledged MVC framework
    * It provides a strong opinion on how the application should be structured and offers **bi-directional* data flow and updates to real **DOM**.
*  MVC is an architectural pattern that separates the application layer into **Model, View, and Controller**.


* **Model**: relates to all the data related logic.
* **View**: is used for UI logic of the application.
* **Controller**: the brain of the setup; It is an interface between the model and view. 


# **Advantages of Angular**

* Custom components - Allows you to build your own componenets that can pack functionality along with rendering logic into reusable pieces.

* Data binding - Allows you to effortlessly move your data from your Javascript code to the view and react to user events without having to write any code yourself.

* Dependency Injection - Allows you to write modular services and have them injected wherever they are needed. This greatly improves the testability and reusability of the same. 

* Testing - Angular has been built from the ground up. With testability in mind you can literally test every part of the application.

* Comprehensive - Angular is a full-fledged framework and provides out-of-the-box solutions for server communication, routing, and more.

* Browser compatibility - Angular is cross platform and browser compatible. An Angular application can typically run on all browsers, ie. Chrome, Firefox, Safari, and platforms
  like Windows, Mac OS, and Linux
  
  
# **Limitations of Angular**

* Steep learning curve - Since Angular is a complete full-fledged framework it becomes difficult for learners to begin with. You need to be acquanted with simple topics and then   move on to more advanced topics to become proficient in this language.

* Limited SEO options - Angular offers limited SEO options and poor accessibility to search engine crawlers.

* Verbose and complex - A common issue faced by the angular community is the verbosity of the framework. It also poses to be complex compared to other front-end tools

* Migration - It becomes difficult to port legacy code to angular style architecture. Also with each new release it's painful to upgrade and a lot of the them are not backwards   compatible. 

# **Angular Learning Curve**

* Basic topics in angular to be learned are:
    * Directives
    * Modules
    * Decorators
    * Components
    * Services
    * Dependency Injection
    * Pipes and templates

* Advanced topics include:
    * Change detection
    * Zones
    * AoT compilation
    * Rx.js
* *The learning curve is clear-cut and becomes easier over time* 


# **Companies using Angular**

* Some top tier companies that use angular are:
    * Nike
    * Google
    * Upwork
    * Forbes
    * HBO
    * Sony
    * GM - General Motors
 
# **Angular Pre-requisutes**

* NodeJS:
    * Angular uses NodeJS as its base for a large part of its build environment

* Angular CLI:
    * Angular team has created a command-line interface tool to make it easier to bootstrap and develop angular applications
    * Installation command:
*     npm install -g @angular/cli
    * Confirmation:
*     ng --version
    
* IDE or text editor:
    * Visual studio code is a powerful source code editor that is available on Windows, Mac OS, and Linux platforms


# **Whats in it for you?**

* What are angular components?
* Creating an angular component.
* Component decorator metadata.

# **What are Angular components?**

* Consider components as lego blocks, they basically are combined together to form the final application.
  * ie:
      * logo component
      * sign in component
      * create account component
      * image component
* Generally these components don't affect the working of each other, but however when embedded the define the UI of your application

# **Common features**

* They are the building blocks of an application. Generally you have a root component which is basically the app component and then it branches out into other components           creating a hierarchy.
* Angular components are a subset of directives 

