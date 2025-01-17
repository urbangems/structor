Structor - a user interface builder for Web applications with React UI
----------

[![facebook group](https://img.shields.io/badge/facebook%20group-follow-blue.svg?style=flat)](https://www.facebook.com/groups/structor/)
[![Twitter Follow](https://img.shields.io/twitter/follow/@helmetrex.svg?style=social)](https://twitter.com/StructorMarket)

[![npm version](https://img.shields.io/npm/v/structor.svg?style=flat)](https://www.npmjs.com/package/structor)
[![npm downloads](https://img.shields.io/npm/dt/structor.svg?style=flat)](https://www.npmjs.com/package/structor)

<img src="https://github.com/ipselon/structor/blob/master/images/title-background.png" style="width: 100%;"></img>

Structor was developed to overcome many challenges in Web application development. It’s a fast and handy tool for the visual construction of User Interface from a pre-created components.

### Features

* Visual combining of interface elements utilising well known WYSIWYG principals. You always get the instant feedback - how your UI-components look, feel, how they can interact with each other and with User.

* A unique flexible and configurable code generation. UI developer is able to configure the existing code generators or create his own code generator. Both options are quick and simple. And the result is - clear and clean code generated with taking into account your preferable design patterns.

* <a href="https://helmetrex.com/generators">Installable online source code generators</a>, which are designed to eliminate the efforts to create advanced components, which require the source code infrastructure in order to interact, for example, with RESTful service or with each other. 

* Advanced documentation features for components. All components used in Structor has built-in documentation. Thus, it’s easy and convenient to configure and modify components within Structor.

* Structor works with specially crafted projects - bundles with a sets of simple basic components or components with an advanced complicated logic. It’s really easy to reuse components in Structor.

* Structor’s Team support. We are providing service support both for integration of Structor into your development process and overall fulfillment.

The builder runs locally as HTTP server with ```webpack-dev-middleware``` + ```webpack-hot-middleware``` + ```react-transform-hmr``` inside.
So, the builder can be used as an HTTP server with all hot reloading capabilities from the box.

Watch the presentation about how Structor works. This presentation shows all capabilities of Structor as development tool and describe its user interface controls: [How does Structor work ?](http://slides.com/alexanderpustovalov/deck)


### Videos

* [Videos on Structor Market](https://helmetrex.com/videos)
* [Spring Data REST Bootstrap prepack intro](https://www.youtube.com/watch?v=ag57pjaW9F8)
* [Fetch data from GitHub | Part 1](https://www.youtube.com/watch?v=AY65e6Ry_rY)
* [Fetch data from GitHub | Part 2](https://www.youtube.com/watch?v=JLz8B0XJPyk)
* [Speed designing of ToDo list](https://www.youtube.com/watch?v=PggnIYdaJFI&list=PLAcaUOtEwjoR_U6eE2HQEXwkefeVESix1&index=3)

### List of existing projects on GitHub

* [sdr-bootstrap-prepack](https://github.com/ipselon/sdr-bootstrap-prepack)
* [bootstrap-prepack](https://github.com/ipselon/bootstrap-prepack)
* [material-ui-prepack](https://github.com/ipselon/material-ui-prepack)

### Articles

* [Using React Router inside of components](https://github.com/ipselon/structor/wiki/Using-React-Router-inside-of-components)
* [Structor's component model representation](https://github.com/ipselon/structor/wiki/Structor's-component-model-representation)
* [Generators metadata overview](https://github.com/ipselon/structor/wiki/Generators-metadata-overview)
* [Shortcuts](https://github.com/ipselon/structor/wiki/Structor-shortcuts)
* [Troubleshooting](https://github.com/ipselon/structor/wiki/Trobleshooting)

### Tutorials

* [Fetch data from GitHub (part 1)](https://github.com/ipselon/structor/wiki/Structor-tutorial:-%22Fetch-data-from-GitHub%22-(part-1))
* [Fetch data from GitHub (part 2)](https://github.com/ipselon/structor/wiki/Structor-tutorial:-%22Fetch-data-from-GitHub%22-(part-2))

### Getting started

Install Structor in global scope:
```
npm install structor -g
```

Then you have two ways to start working in the builder.

The first way:
* Create an empty folder on local machine.
* cd to this folder and run command: ```structor```.
* Open the browser and enter the address: ```http://localhost:2222/structor```.
* Choose suitable prepack and click clone option.
* Start composing UI...

The second way:
* Go to Structor Market [http://helmetrex.com](http://helmetrex.com), choose suitable boilerplate.
* Download package on localhost and unpack it in some empty folder.
* cd to this folder and run ```npm install``` command.
* Once installation is finished run ```structor```.
* Open the browser and enter the address: ```http://localhost:2222/structor```.
* Start composing UI...
 
The next time you want to open project in Structor, just go to the folder where project is and run ```structor```.

##### Tips
* To run with different port: ```structor -p <port>```<br/>
* To specify different project's working directory: ```structor -d <path_to_project_dir>```

#### License
Apache License, Version 2.0 (Apache-2.0)
