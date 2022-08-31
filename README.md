# このリポジトリについて

コーディング面談で使うための素のTypeScript実行環境です。

[TypeScript Deep Dive 日本語版](https://typescript-jp.gitbook.io/deep-dive/)をベースに構築してあります。

ライブラリ

* TypeScript
* React
* date-fns

開発用ライブラリ

* Jest (TypeScript対応)
* Tesint Library (DOM/React)

## Docker(docker-compose)で実行する場合

```sh
# ライブラリのインストール (ボリュームマウントされるので、node_modulesが作成されます)
$ docker-compose run local npm install
# 単体テスト実施
$ docker-compose run local npm test 
```