# note_julia_bayes

これは、講談社から出版された「Juliaで作って学ぶベイズ統計学」（須山, 2021）を写経しながら読んでいく記録を綴るリポジトリです。
もしもどなたかの参考になるようでしたら幸いです。

なお本リポジトリは、著者、出版社等とは一切の関係はありません。

## 環境構築

docker（`jupyter/datascience-notebook` image）を使って環境を作っています。詳細は`docker-compose.yml`を参照ください。

コンテナの起動は本リポジトリをcloneしてできたディレクトリで、以下のコマンドを実行。

```bash
docker-compose up -d
```

ターミナルからログを確認するには以下のコマンド。

```bash
docker-compose logs -f
```

コンテナを立ち上げると、自動でjupyter labが立ち上がります。port番号などは各自の環境に合わせてセットしてください。
コンテナが正常に立ち上がっていれば、以下のURLでjupyter labにアクセスできます。

[http://localhost:8101](http://localhost:8101)

## 参考

- [github: sammy-suyama/BayesBook](https://github.com/sammy-suyama/BayesBook)
  - 公式のサポートページです
