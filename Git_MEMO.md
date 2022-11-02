# Git学習メモ
## Gitコマンド

## Gitインストール後の初期設定
- Gitの初期設定を行うgit configコマンド
  - git config --global user.name motoi-daichi
- 設定値の一覧を確認
  - git config --list
- 特定の設定値を確認
  - git config user.name

設定例）
```
$ git config --global user.name motoi-daichi
$ git config --global user.email goodddd@gmail.com
$ git config --list
$ git config --global core.editor "code --wait"/"atom --wait"
$ git config core.editor
```

- ローカルリポジトリを作る
  - git init
- ファイルの状態を確認
  - git status
- ファイルを登録する
  - git add


