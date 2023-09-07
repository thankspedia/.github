🍵 Kombucha.js 
==================
**Kombucha.js** is (at least we believe) the easiest, the most robust, zero
dependent, and opinionated all-in-one frontend/backend application framework.

 ⛩️ Design Goal🗼 
==================
As the design goal of **Kombusha.js**, there are five agendas.

1. Implement a reliable development environment without complicating
   transpilers such as Babel TypeScript.
2. Offer practical methods to access databases directly without any
   Object-Relational Mapping (ORM) solutions.
3. Make the development process as simple as possible such that merely Vim in a
   terminal-emulator without fancy editors is sufficient.
4. Enable developments of super-large scalable database systems as if it were
   [AS/400](https://en.wikipedia.org/wiki/IBM_AS/400).
5. The applications must sustainablly run without manual maintanance for
   decades.

  🐶 Features
================
- Zero dependent framework
- It runs out of the box
- Built-in JWT like authentication scheme
- Built-in runtime typecheck/schema validator
- NO ORM based programming SQL without object mapping


  Zero-Dependent Framework
----------------------------
**Kombucha.js** is (almost) zero-dependent framework; that is, Kombucha.js uses
no module from other projects.  All modules in **Kombucha.js** are developped
by developpers of **Kombucha.js** its own. Still each of them is able to be
used as an independend module.

  Others
-----------------------
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

  Thankspedia
===============
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
