 .github の注意点
==================

このリポジトリによって Thankspedia のプロフィール画面を編集することが出来ます。

- GitHubオーガニゼーションは、.github/profile/README.md という名称のREADMEファイルをオーガニゼーションのプロフィールとして表示する。
- 現在 [./profile/README-eng.md](./profile/README-eng.md) 及び [./profile/README-jpn.md](./profile/README-jpn.md) の２つのファイルを profile ディレクトリに配置している。
- [./profile/README.md](./profile/README.md) は [./profile/README-jpn.md](./profile/README-jpn.md) へのシンボリックリンクになっている。
- GitHub 上ではシンボリックリンクの編集を行うことが出来ないので、一旦ローカル上にクローンしてから作業する必要がある。

以上です。
