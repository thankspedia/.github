🍵 Kombucha.js 
==================
**Kombucha.js** is (at least we believe) the easiest, the most robust, zero
dependent, and opinionated all-in-one frontend/backend application framework.

  🐶 Features
================
- Zero dependent framework
- It runs out of the box
- Built-in JWT like authentication scheme
- Built-in runtime typecheck/schema validator
- NO ORM based programming SQL without object mapping

 ⛩️ Design Goal🗼 
==================
As the design goal of **Kombusha.js**, there are the six agendas.

1. Enable development both frontend applications and backend applications seamlessly and simultaneously.
2. Implement a reliable development environment without complicating
   transpilers such as Babel TypeScript.
3. Offer an infrastructure to implement Remote Procedure Call between frontend applications and backend applications so that a frontend application can access to methods on an backend application as if    the methods are deployed in the frontend application.
4. Offer practical methods to access databases directly without any
   Object-Relational Mapping (ORM) solutions.
5. Make the development process as simple as possible such that it is
   sufficient to use only [Vim][] in a terminal-emulator for the development. It
   should not be necessary to use fancy editors such as VSCode or others.
6. Enable developments of super-large scalable database systems as if it were
   [AS/400](https://en.wikipedia.org/wiki/IBM_AS/400).
7. The applications must sustainablly run without manual maintanance for
   decades.

[Vim]: https://www.vim.org/

### Zero-Dependent Framework
**Kombucha.js** is (almost) zero-dependent framework; that is, Kombucha.js only uses
the modules which are developped within Kombucha.js itself and adopts no module from other projects.
All modules in **Kombucha.js** are developped
by developpers of **Kombucha.js** its own while each of them is also able to be
used as an independend module.

### Others
In backend development, you can scalably design web API as if they are simple
Node.js's module functions. In frontend development, you can access these API
as if they are simple module functions deployed as simpe ESM module.

It includes a unique frontend application framework called [react-rerenderers][]
which frees developpers from nasty Infinite Rendering Loops, devilish Prop
Drilling Hell, diabolical Provider Hell and other evil state.

In frontend application, you can access to the backend API server as if they
are only functions on the modules deployed in the frontend; this will
drastically reduce pain from frontend development.

It consists many new ideas to accomplish efficiency of development; such as
[runtime-typesafety][] which implements input/output validation on runtime, or as
[vanilla-schima-validator][] which allows you to find missing and wrong typed
field values in your JSON requests right after you did something wrong.

[react-rerenderers]: https://github.com/kombucha-js/react-rerenderers/
[vanilla-schima-validator]: https://github.com/kombucha-js/vanilla-schima-validator/
[runtime-typesafety]: https://github.com/kombucha-js/runtime-typesafety/


 Frontend Development with Kombucha.js
======================================
Kombucha.js defines a convention which every **Kombucha.js** frontend application should
follow. It is described in [Frontend Development with Kombucha.js][frontend].


 Backend Development with Kombucha.js
======================================
There is a convention which defines the form of every module for the backend
application with **Kombucha.js**. For further information, please see [Backend Development with Kombucha.js][backend].


[frontend]: https://github.com/kombucha-js/.github/wiki/Frontend-Development
[backend]: https://github.com/kombucha-js/.github/wiki/Backend-Development



  🙏🏿 🥰 Thankspedia Project 🥰 🙏🏻
========================================
**Kombucha.js** is developped as a part of a project called [Thankspedia][].
Thankspedia is a project to implement an infrastracture for thankfulness, not
for money; it tries to transfer not an amount of money, but an amount of
thankfulness. For further information about Thankspedia, please refer its
[website][Thankspedia].

[Thankspedia]: https://github.com/thankspedia/


🌈 Contribution guidelines
---------------------------------------------------------------
- how can the community get involved?

**Kombucha.js** is distributed as GPL v3.0.

Please send feedbacks or report issues at [github.com](https://github.com/kombucha-js)

The primary maintainer is [Atsushi Oka][ats4u].

I am working in a company in Akihabara, Tokyo.

If you happen to pass by, please send us a message 😄

[ats4u]: https://github.com/ats4u

<!--
**Here are some ideas to get you started:**
👩‍💻 Useful resources
---------------------------------------------------------------
 - where can the community find your docs? Is there anything else the community should know?
🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
