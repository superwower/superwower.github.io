# superwower.github.io
superwowerのgithub page用レポジトリです。
[Jekyll](https://jekyllrb.com/)という静的ウェブページ作成ツールを使っています。

# Requirements
ローカルで動作確認をする場合は以下のツールが必要です。
- Ruby >=2.2.5
- Gem
- gcc, make

# Development
ローカルで開発するための準備、必要に応じてsudoなどをつけてください。
```
$ git clone https://github.com/superwower/superwower.github.io.git
$ cd superwower.github.io
$ gem install bundler jekyll
$ bundle install
$ bundle exec jekyll serve
```

# After joining this team
github.io の members にあなたを追加しましょう！
1. Requirements に必要なツールをインストールしてください
1. Development の手順に従って、本リポジトリの開発にに向けた準備をお願いします
1. メンバー情報追加用の新しいブランチを作成しましょう
1. 「_config.yml」 ファイルの members に自身の情報を追加してください
    ```yaml
    members: 
      - name    : kut-arika                                           // GitHub のアカウント名
        image   : https://avatars2.githubusercontent.com/u/5959324    // GitHub のアカウントの写真(Your Profile の画像右クリックで）
        twitter : https://twitter.com/kut_arika                       // TwitterアカウントのURL(必須ではないです)
    ```
1. commit & push をして、masterブランチへのプルリクエストを出しましょう

# Contribution
プルリクを投げてください。

# License
MIT
