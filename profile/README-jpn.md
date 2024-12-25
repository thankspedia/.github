  Thankspedia.js 
===================
**サンクスペディア.js** は、株式会社東京技術計算コンサルタント倉川　清志社長が提唱する「感謝のインフラ」を実現する為に作成されたフレームワークです。

世界を感謝の気持ちで溢れさせる為のインフラ基盤として設計されたサンクスペディア.jsは、オピニオネイテッド型フレームワークを採用、RPC(リモートプロシージャ呼び出し）を実装しました。
このアーキテクチャによりフロントエンドからシームレスにバックエンドのAPIを呼び出しが可能となり、迅速な開発が実現します。

サンクスペディア.jsは Node.js/Firefox/Chrome等々のESM2022以降のJavaScriptに対応した実行環境で動作します。

  特徴
================  
- AS/400 を理想としたアーキテクチャを模倣
- 簡易性より安定性を重視した設計
- フロントエンド／バックエンドを区別せずに同時に開発するスタイル
- マルチユーザー・マルチオーガニゼーションの認証にデフォルトで対応
- 自動バリデーション
- ORM利用を強制しないデータベース駆動の開発
- 実行時型チェック
- フロントエンドは高速な Vine を採用
- バベルへの依存性を排除
- ターミナル画面を基盤に置いたポータブルかつ軽量な開発環境

サンクスペディア.js は、従来のJavaScript開発での弱点だった実行型チェックに対応しています。
実行時に受け取った予期しないデータは、予想できない挙動を引き起こしトラブルシュートに時間が掛かりがちです。
これらの予期しない実行時の誤動作を検知し未然にエラーとして報告することが可能です。

[Vim]: https://www.vim.org/

 Table of Contents
------------------------------------

[TOC-BEGIN]: <> ""
[TOC-END]: <> ""
[TOC-COMMAND]: <> "r! cat profile/README.md | pandoc -s --toc --wrap=none  --from=markdown --to=markdown | sed -n '1,/^ *$/p'"


 Frontend Development with Thankspedia.js
----------------------------------------

[React-Rerenderers.js][rerenderers] is a simple and yet effective framework for
frontend application development. It should preferably, but not necessarily be
used in Thankspedia.js frontend applications.

[React-Rerenderers.js][rerenderers] define some coding conventions. Thankspedia.js
recommends applications to follow the conventions. For further information
about the conventions, see [React-Rerenderers.js][rerenderers] official
documentation.

[frontend]: https://github.com/kombucha-js/.github/wiki/Frontend-Development


 Backend Development with Thankspedia.js
---------------------------------------
There is a convention which defines the form of every module for the backend
application with **Thankspedia.js**. For further information, please see [Backend Development with Thankspedia.js][backend].

[backend]: https://github.com/kombucha-js/.github/wiki/Backend-Development


 Modules
------------------------------------

Thankspedia.js consists sixteen modules.

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
**Thankspedia.js** is developed as a part of a project called [Thankspedia][].
Thankspedia is a project to implement an infrastructure for thankfulness, not
for money; it tries to transfer not an amount of money, but an amount of
thankfulness. For further information about Thankspedia, please refer its
[website][Thankspedia].

[Thankspedia]: https://github.com/thankspedia/


🌈 Contribution guidelines
---------------------------------------------------------------
- how can the community get involved?

**Thankspedia.js** is distributed as GPL v3.0.

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
