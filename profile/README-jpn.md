  サンクスペディア.js 
===================
**サンクスペディア.js** は、株式会社東京技術計算コンサルタント倉川　清志社長が提唱する「感謝のインフラ」を実現する為に作成されたフレームワークです。

世界を感謝の気持ちで溢れさせる為のインフラ基盤として設計されたサンクスペディア.jsは、オピニオネイテッド型フレームワークを採用、RPC(リモートプロシージャ呼び出し）を実装しました。
このアーキテクチャによりフロントエンドからシームレスにバックエンドのAPIを呼び出しが可能となり、迅速な開発が実現します。

サンクスペディア.jsは Node.js/Firefox/Chrome等々のESM2022以降のJavaScriptに対応した実行環境で動作します。

現在サンクスペディア.js は、株式会社東京技術計算コンサルタントにて社内で社員同士が感謝の気持ちをブロックチェーン上でやり取りし、賞与に反映する仕組み「サンクスペディア/tBC」を実装し、稼働中です。

  特徴
================  
- AS/400 を理想としたアーキテクチャを模倣
- 簡易性より安定性を重視した設計
- フロントエンド／バックエンドを区別せずに同時に開発するスタイル
- マルチユーザー・マルチオーガニゼーションの認証にデフォルトで対応
- 自動バリデーション
- ORM利用を強制しないデータベース駆動の開発
- 実行時型チェック
- フロントエンドでは、高速なVineを採用
- バベルへの依存性を排除
- ターミナル画面を基盤に置いたポータブルかつ軽量な開発環境

サンクスペディア.js は、従来のJavaScript開発での弱点だった実行型チェックに対応しています。
実行時に受け取った予期しないデータは、予想できない挙動を引き起こしトラブルシュートに時間が掛かりがちです。
これらの予期しない実行時の誤動作を検知し未然にエラーとして報告することが可能です。

 モジュール一覧
------------------------------------

**サンクスペディア.js** は約１５個のモジュールによって構成されています。それぞれのモジュールは独立しており、個別に利用することが可能です。

| Name                                                                    | Description                                                                                    |
| ----------------------------------------------------------------------  | ---------------------------------------------------------------------------------------------  |
| [react-rerenderers.js][react-rerenderers]                               | フロントエンド・アプリケーションの為のフレームワーク                                                    |
| [mixin-prototypes][mixin-prototypes]                                    | 多重継承を実現する。ユーザーが定義したAPIをバックエンド上で実行する為、実行時に全APIの結合を行う。            |
| [asynchronous-context][asynchronous-context]                            | 非同期関数の実行経路を追跡する為のフレームワーク。非同期関数として定義されたAPI関数群をcontextクラスと呼ぶ。   |
| [asynchronous-context-rpc][asynchronous-context-rpc]                    | RPC（リモートプロシージャコール）を実装するフレームワーク。contextクラスとして定義されたAPIをサービスとして起動する為のツール群を提供       |
| [authentication-context][authentication-context]                        | 認証を行う為のフレームワーク。 asynchronous-context 上で動作するcontextクラス。                        |
| [database-postgresql-context][database-postgresql-context]              | PostgreSQLの呼び出しを行う。asynchronous-context 上で動作する context クラス                         |
| [database-postgresql-query-builder][database-postgresql-query-builder]  | asynchronous-context API を定義する為のテンプレートを生成する。現在利用されていない。                    |
| [crypto-web-token][crypto-web-token]                                    | フロントエンドアプリケーションの認証で利用する bearer トークン認証を実装する。                             |
| [prevent-undefined][prevent-undefined]                                  | タイプミスによる変数名間違い・フィールド名間違い等々のプログラム上のエラーを検知する。現在利用されていない。廃止予定。     |
| [fold-args][fold-args]                                                  | 名前付き引数と引数オーバーライドを定義するフレームワーク。                                               |
| [runtime-typesafety][runtime-typesafety]                                | 実行時型チェックを実現する。関数呼び出しの異常な入力値と異常な出力値を検出し、エラーとして報告する。            |
| [vanilla-schema-validator][vanilla-schema-validator]                    | 非オピニオネイテッドなバリデーション処理を行う為のフレームワーク、及びツール郡を提供する。                    |
| [sql-named-parameters][sql-named-parameters]                            | PostgreSQLの為の SQL 名前付きパラメータを実装する。                                                  |
| [sqlmacro][sqlmacro]                                                    | SQL上で ASP/PHPのような動的SQL生成を実現するためのフレームワーク                                        |
| [randomcat][randomcat]                                                  | 未使用。廃止予定。                                                                                |
| [beep][beep]                                                            | 未使用。廃止予定。                                                                                 |

[rerenderers]:                       https://github.com/thankspedia/react-rerenderers/
[react-rerenderers]:                 https://github.com/thankspedia/react-rerenderers/
[asynchronous-context]:              https://github.com/thankspedia/asynchronous-context/
[asynchronous-context-rpc]:          https://github.com/thankspedia/asynchronous-context-rpc/
[prevent-undefined]:                 https://github.com/thankspedia/prevent-undefined/
[fold-args]:                         https://github.com/thankspedia/fold-args/
[runtime-typesafety]:                https://github.com/thankspedia/runtime-typesafety/
[database-postgresql-query-builder]: https://github.com/thankspedia/database-postgresql-query-builder/
[vanilla-schema-validator]:          https://github.com/thankspedia/vanilla-schema-validator/
[sql-named-parameters]:              https://github.com/thankspedia/sql-named-parameters/
[sqlmacro]:                          https://github.com/thankspedia/sqlmacro/
[mixin-prototypes]:                  https://github.com/thankspedia/mixin-prototypes/
[authentication-context]:            https://github.com/thankspedia/authentication-context/
[database-postgresql-context]:       https://github.com/thankspedia/database-postgresql-context/
[crypto-web-token]:                  https://github.com/thankspedia/crypto-web-token/
[randomcat]:                         https://github.com/thankspedia/randomcat/
[beep]:                              https://github.com/thankspedia/beep/

[LIST-COMMAND]: <> "gh repo list --json 'url' thankspedia --jq '.[].url'"

