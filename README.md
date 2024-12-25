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
as [vanilla-schema-validator][] which allows you to find missing and wrong typed
field values in your JSON requests right after you did something wrong.

It also includes a unique frontend application framework called [React-Rerenderers.js][rerenderers]
which frees developers from annoying problems which you often encounter in
React.js application development such as Infinite Rendering Loops, Prop Drilling
problem, Provider Hell and other problems. For further information, see
[React-Rerenderers.js][rerenderers].

  🐶 Features 🐶
-----------------
- [Babel Free](https://art-deco.github.io/nodetools/babel-when-open-source-is-not-free-sofware.html)
- It runs out of the box
- Very unique architecture which offers you simplicity in extreme
- Prioritize durability and robustness than easiness
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


 Frontend Development with Kombucha.js
----------------------------------------

[React-Rerenderers.js][rerenderers] is a simple and yet effective framework for
frontend application development. It should preferably, but not necessarily be
used in Kombucha.js frontend applications.

[React-Rerenderers.js][rerenderers] define some coding conventions. Kombucha.js
recommends applications to follow the conventions. For further information
about the conventions, see [React-Rerenderers.js][rerenderers] official
documentation.

[frontend]: https://github.com/kombucha-js/.github/wiki/Frontend-Development


 Backend Development with Kombucha.js
---------------------------------------
There is a convention which defines the form of every module for the backend
application with **Kombucha.js**. For further information, please see [Backend Development with Kombucha.js][backend].

[backend]: https://github.com/kombucha-js/.github/wiki/Backend-Development


 Modules
------------------------------------

Kombucha.js consists sixteen modules.

| Name                                                                    | Description                                                                                    |
| ----------------------------------------------------------------------  | ---------------------------------------------------------------------------------------------  |
| [React-Rerenderers.js][react-rerenderers]                               | A framework for frontend applications                                                          |
| [mixin-prototypes][mixin-prototypes]                                    | An implementation of multiple inheritance                                                      |
| [Asynchronous-Context][asynchronous-context]                            | The super class for the objects defines all backend API methods                                |
| [Asynchronous-Context-RPC][asynchronous-context-rpc]                    | A RPC-like framework for secure transactions between frontend and backend via https            |
| [Authentication-Context][authentication-context]                        | Offer an abstract interface to implement login and logout                                      |
| [Database-Postgresql-Context][database-postgresql-context]              | Offer a way to access PostgreSQL database servers                                              |
| [database-postgresql-query-builder][database-postgresql-query-builder]  | An utility to build queries for PostgreSQL automatically                                       |
| [crypto-web-token][crypto-web-token]                                    | Implement a JWT-like web token framework                                                       |
| [prevent-undefined][prevent-undefined]                                  | Throw an error when it detected an access to a non-existing field                              |
| [fold-args][fold-args]                                                  | Define a stable protocol to implemenent named arguments for methods                            |
| [runtime-typesafety][runtime-typesafety]                                | Watch for input/output of methods and throw an error when it detected an unexpected value      |
| [vanilla-schema-validator][vanilla-schema-validator]                    | A non-opinionated JavaScript schema validator; or a duck-typing runtime-type detector          |
| [sql-named-parameters][sql-named-parameters]                            | Replace all keyword starts with a dollar sign as a named-parameter in SQL                      |
| [sqlmacro][sqlmacro]                                                    | Implement ASP-like syntax in SQL                                                               |
| [randomcat][randomcat]                                                  | An additional module which offers a function to generate a name of a cat randomly              |
| [beep][beep]                                                            | An additional module to play a beep tone with a specified musical pitch                        |

[randomcat]:                         https://github.com/kombucha-js/randomcat/
[beep]:                              https://github.com/kombucha-js/beep/

[rerenderers]:                       https://github.com/kombucha-js/react-rerenderers/
[react-rerenderers]:                 https://github.com/kombucha-js/react-rerenderers/
[asynchronous-context]:              https://github.com/kombucha-js/asynchronous-context/
[asynchronous-context-rpc]:          https://github.com/kombucha-js/asynchronous-context-rpc/
[prevent-undefined]:                 https://github.com/kombucha-js/prevent-undefined/
[fold-args]:                         https://github.com/kombucha-js/fold-args/
[runtime-typesafety]:                https://github.com/kombucha-js/runtime-typesafety/
[database-postgresql-query-builder]: https://github.com/kombucha-js/database-postgresql-query-builder/
[vanilla-schema-validator]:          https://github.com/kombucha-js/vanilla-schema-validator/
[sql-named-parameters]:              https://github.com/kombucha-js/sql-named-parameters/
[sqlmacro]:                          https://github.com/kombucha-js/sqlmacro/
[mixin-prototypes]:                  https://github.com/kombucha-js/mixin-prototypes/
[authentication-context]:            https://github.com/kombucha-js/authentication-context/
[database-postgresql-context]:       https://github.com/kombucha-js/database-postgresql-context/
[crypto-web-token]:                  https://github.com/kombucha-js/crypto-web-token/
[randomcat]:                         https://github.com/kombucha-js/randomcat/
[beep]:                              https://github.com/kombucha-js/beep/

[LIST-COMMAND]: <> "gh repo list --json 'url' kombucha-js --jq '.[].url'"



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
