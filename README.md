
## Go言語でのSOLID原則とデザインパターンの実装例

このリポジトリは､"Go言語でトレーディングボット実装する"という例題をもとに､SOLID原則とデザインパターンを学習していきます｡

下記二冊の本と講座の学習メモとして､このリポジトリを更新していきます｡

- Java言語で学ぶデザインパターン入門 結城 浩 著
- Clean Architecture Rebers C Martin 著
- 脱オブジェクト指向初心者！】TypeScriptで学ぶSOLID原則・デザインパターン Yu shinozaki作


## なぜ､SOLID原則とデザインパターンが必要なのか?

現在､私はGO言語でシステムトレードのバックテストとDYDXでのAPI取引を内蔵したプラットフォームを開発しています｡

設計を甘く見積もったせいで､痛い目を見ています｡

具体的には､構造体に新たなメソッドを追加した後､そのメソッドに対応させるために､ほぼすべてのコードをリファクタリングしなくてはいけなくなっています｡

このような糞コードを二度と書かないために､クリーンで拡張可能性が高いコードとはどのようなものなのか?上記二冊から学習したいと考えています｡