# SAIL

## What is SAIL?

<div style="padding: 1em; margin: 1em; background-color: #ff0; color: #000">Sail is being prepared for release and will be released by Monday Aug 10</div>

What SAIL is currently and what SAIL hopes to be are, unfortunately, still a little more different than I wish.


Currently, SAIL is a code generator, basically.  It is written in PHP, but can use PHP or Typescript as a compilation target.  Practically this means you write SAIL code, run it through a PHP tool, and out pops more PHP _or_ Typescript.

It is meant to be a general purpose, highly safe, secure, and easy to use programming language and software development environment.  The _language itself_ isn't mind bending -- although no expense was spared insofar as one individual can go.  What makes Sail something (hopefully) worthwhile is 

1. the particularly unique _combination_ of features it has 
2. combined with the intermediate representation of the language 
3. which, between both of them, without being messy and bloated, represents a very large band of development tasks and styles: that is, the concept here is that Sail would be useful to write anything.  examples:
4. the way the language is implemented and
5. the overall goals and tenants of the language
6. the environment as a whole.

The end goal is that eventually Sail would be able to express the following apps cleanly:

 - a single-page modern web application with server-side    - and client-side intelligent rendering
 -  a throw-away bash script
 -  a Desktop GUI application
 - a simple 3D mobile game
 -  a high-performance concurrent network server (daemon)    - which can scale both horizontally and vertically  -   effortlessly
 - a browser extension
 - an interactive console script
 - firmware on an unusual CPU architecture which requires careful memory management
 - an app which shares interface/code between web app, mobile app, desktop app.

The magic of Sail is that it is built from the ground up on language extension system.  Every feature (even the _core language_) is built on the same tools you, a developer of Sail, has at their disposal.  You don't have to use this system and in fact you are encouraged to leave it alone unless you really know what you are doing - however for those use cases which do exist - it is there and waiting.

