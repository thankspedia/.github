 🍵 Kombucha.js 🍵
===================

**Kombucha.js** is (at least we believe) the easiest, the most robust,
zero-dependent, and strongly opinionated all-in-one frontend/backend application
framework.

With Kombucha.js, you can scalably design web API methods and the methods can be
deployed with minimum overhead. Frontend applications can access to the API
methods with minimum overhead as if they are general functions deployed in ESM
modules.

It includes many new ideas to accomplish efficiency of development; such as
[runtime-typesafety][] which implements input/output validation on runtime, or
as [vanilla-schima-validator][] which allows you to find missing and wrong typed
field values in your JSON requests right after you did something wrong.

It also includes a unique frontend application framework called [React-Rerenderers.js][rerenderers]
which frees developers from annoying problems which you often encounter in
React.js application development such as Infinite Rendering Loops, Prop Drilling
problem, Provider Hell and other problems. For further information, see
[React-Rerenderers.js][rerenderers].

  🐶 Features 🐶
-----------------
- It runs out of the box
- Very unique architecture which offers you simplicity in extreme
- Prioritize durability and robustness
- Zero-dependent
- Built-in JWT like authentication scheme
- Built-in runtime typecheck/schema validator
- NO ORM based programming SQL without object mapping

 🗼 Design Goal 🗼
-------------------
As the design goal of **Kombucha.js**, there are seven agendas.

1. Enable development both frontend applications and backend applications
   seamlessly and simultaneously.
2. Implement a reliable development environment without complicating
   transpilers such as Babel TypeScript.
3. Offer an infrastructure to implement Remote Procedure Call between frontend
   applications and backend applications so that a frontend application can
   access to methods on an backend application as if    the methods are deployed
   in the frontend application.
4. Offer practical methods to access databases directly without any
   Object-Relational Mapping (ORM) solutions.
5. Make the development process as simple as possible such that it is
   sufficient to use only [Vim][] in a terminal-emulator for the development. It
   should not be necessary to use fancy editors such as VSCode or others.
6. Enable developments of super-large scalable database systems as if it were
   [AS/400](https://en.wikipedia.org/wiki/IBM_AS/400).
7. The applications must sustainably run without manual maintenance for
   decades.

[Vim]: https://www.vim.org/


 Table of Contents
------------------------------------

[TOC-BEGIN]: <> ""


[TOC-END]: <> ""
[TOC-COMMAND]: <> "r! cat profile/README.md | pandoc -s --toc --wrap=none  --from=markdown --to=markdown | sed -n '1,/^ *$/p'"

### Others



[rerenderers]:               https://github.com/kombucha-js/react-rerenderers/
[vanilla-schima-validator]:  https://github.com/kombucha-js/vanilla-schima-validator/
[runtime-typesafety]:        https://github.com/kombucha-js/runtime-typesafety/


 Frontend Development with Kombucha.js
----------------------------------------

[React-Rerenderers.js][rerenderers] is a simple and yet effective framework for
frontend application development. It should preferably, but not necessarily be
used in Kombucha.js frontend applications.

[React-Rerenderers.js][rerenderers] define some coding conventions. Kombucha.js
recommends applications to follow the conventions. For further information
about the conventions, see [React-Rerenderers.js][rerenderers] official
documentation.


 Backend Development with Kombucha.js
---------------------------------------
There is a convention which defines the form of every module for the backend
application with **Kombucha.js**. For further information, please see [Backend Development with Kombucha.js][backend].


[frontend]: https://github.com/kombucha-js/.github/wiki/Frontend-Development
[backend]: https://github.com/kombucha-js/.github/wiki/Backend-Development



  🙏🏿 🥰 Thankspedia Project 🥰 🙏🏻
----------------------------------------
**Kombucha.js** is developed as a part of a project called [Thankspedia][].
Thankspedia is a project to implement an infrastructure for thankfulness, not
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
