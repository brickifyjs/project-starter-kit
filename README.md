... WIP ...

# MOTIVATIONS

I worked during three years at [INGENICO](https://www.ingenico.com) France, developing apps, webos, bridges for the new [TELIUM TETRA SMART TERMINALS](https://www.ingenico.com/our-solutions/telium-tetra).

The fastest solutions was definitely Vanilla JS.

I tried [Backbone](http://backbonejs.org/), but [Exoskeleton](http://paulmillr.com/exoskeleton), [webpack](https://webpack.github.io), and [Chaplin](http://chaplinjs.org) were a better alternative.

I tried [React](https://facebook.github.io/react), but [Mithril](https://mithril.js.org) was a better alternative.

The problem was that Mithril did not do sibling redraw and restarted diff from root.

Other VDOM frameworks were slow or did code evaluation and other CSP issues.

That's why I started to work on an embedded systems-friendly VDOM framework that would have a consise syntax, be tiny, be extremely fast, an did sibling redraw.

But I changed my mind and decided to completely rethink my project into something more flexible, open, atomic, and fully customizable…

Anyway, the VDOM Framework is well under development and will soon be release as a BrickJS project.

# GOALS

## Built-in solution for creating JavaScript projects based on Bricks (library, tools, frameworks, websites, etc.) for Node JS and the browser :

* Using Bricks (brick, projects/sub projects/API…) or whatever you name it.
* Using non BrickJS such as Npm modules or other JavaScript code.
* Using private and public domain.

## Be fast and tiny

* Using proven JavaScript techniques and good practices, benchmarking all you are doing.
* Using the smallest bundler that not produces useless code.


## Extend / Override / Define Polymorphism
* Using HOOKS (before and after brick)
* Using closure
* Using direct override
* Using importing modules
* Using bundler hooks
* Using bricks or bricks as a brick middleware
* Using extend brick
* Using Events
* Using config file

## Creating projects using included solutions :
* Using included website generator solution
* Using included pre-built configuration files solution
* Using included js code testing solution
* Using included test coverage solution
* Using included lint code solution
* Using included benchmark tool solution
* Using included bundler solution
* Using included custom build generator solution
* Using included boot strapped github apps and third party solutions
* Using a pre-define architecture solution

By the way you can use your own solution, it's up to you!

# WHAT IS A BRICKJS MODULE ?
A module is a dependency or a dev dependency for core, bricks or projects that can be useful for the community.

It can also be npm dependency or github dependency.

# WHAT IS A BRICK ?
A brick is simply a method that save something into a global store that returns the store's id. 

It can provides a set of methods comming from private of public modules attached to is namespace or others namespaces.

# WHAT IS A PROJECT ?
A project is composed by a set of bricks and non bricks (by the way you can convert all into a brick).

A project can contain sub projects.

It can also be your core.

# WHAT IS A SUB PROJECT ?
A sub project is composed by a pre define build of your projects which used a different set of bricks you have choose.

Or just pre define config file.

# THINKING BRICKJS

BrickJS is designed to be used in an atomic way.

That mean you should think like micro services architecture.

Every bricks could be used with each other.

That why your brick has to be splitted in multiple repository with one single method or multiple methods but not too much in order to keep granularity.

In this case, anyone can reuse your code and just bundle or checkout what he need not else more.

This is very important if you use brickJS as a unique bundle without importing modules manually.


# BUILD MY OWN CORE BASED ON BRICKS AND/OR PROJECTS

# FIND BRICKS

# FIND PROJECTS


# CREATE A BRICK

## Create my first Brick

## Create an advanced Brick


# NEXT

Build BrickJS tools, projects and bricks myself.

Build BrickJS tools, projects and bricks based on community help.

Build your own bricks and projects public or private!



