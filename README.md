# portfolio-3

Check out my new portfolio page. 

![Portfolio 3](https://zno.s3-us-west-1.amazonaws.com/portfolio3.gif)

[Deployed App](https://darrindevs.github.io/portfolio-3/)

## Technologies Used

🏗 JavaScript - JavaScript, often abbreviated as JS, is a programming language that conforms to the ECMAScript specification. JavaScript is high-level, often just-in-time compiled, and multi-paradigm.

🅰️ Typewriter Effect - Typewriter Effect is a simple, but powerful native JavaScript plugin for a cool typewriter effect.

☑️ Git - Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

😺 GitHub - GitHub, Inc. is a provider of Internet hosting for software development and version control using Git.


## Code Snippet 

~~~
var app = document.getElementById('p-intro');

var typewriter1 = new Typewriter(app, {
    loop: true,
    cursor: "👋"
});

$("#p-intro").on({
    mouseenter: function () {
    typewriter1.typeString('<h1>Hey there! I\'m Darrin, a full stack web developer from Oakland, CA.</h1>')
    .pauseFor(2500)
    .typeString('<h1>I\'ve been taking this coding bootcamp at UC Berkeley and making some fun things on the web.</h1>')
    .pauseFor(2500)
    .typeString('<h1>Check out some of my projects.</h1>')
    .pauseFor(10000000000)
    .start()
    }
});
~~~

## Author

🤓 [darrindevs](https://github.com/darrindevs)

