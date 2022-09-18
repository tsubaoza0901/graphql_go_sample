# graphql_go_sample

# 使用方法

## 1．Docker イメージのビルド&コンテナの起動

```
$ docker-compose up -d --build
```


## 2．アプリケーションの起動

```
$ docker exec -it graphql-go-sample bash
```

```
root@fe385569a625:/go/app/src# go run server.go
```

## 3.リクエスト画面

http://localhost:8850/

# 参考URL

## 【公式】
・GraphQL   
https://graphql.org/   

・SWAPI GraphQL API   
https://graphql.org/swapi-graphql   

### ライブラリ（フレームワーク）

・gqlgen：Getting Started   
https://gqlgen.com/getting-started/   

## 【その他】   

・Qiita:GraphQLの全体像とWebApp開発のこれから   
https://qiita.com/saboyutaka/items/171f7382cdf75b67d076   

・Qiita：GraphQLの便利なツール   
https://qiita.com/NagaokaKenichi/items/f83148f4903b17d1d2f0   

・mercari engineering：GraphQLを導入する時に考えておいたほうが良いこと   
https://engineering.mercari.com/blog/entry/20220303-concerns-with-using-graphql/   

・LayerX エンジニアリングブログ：【GraphQL × Go】gqlgenの基本構成とオーバーフェッチを防ぐmodel resolverの実装   
https://tech.layerx.co.jp/entry/2021/10/22/171242   


・Qiita：gqlgenのチュートリアルを試しました   
https://qiita.com/nisitanisubaru/items/a61af89f2a531bb17687   

・GoにおけるGraphQLライブラリ大横断   
https://tech.hicustomer.jp/posts/go-graphql/   
