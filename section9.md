[Section10](https://github.com/koyama86/Agile_Chapter1.2/blob/main/Section10)

# section9 継続的なコードの改善


## 概要
かつて、完成したコードは長い間手を付けられずに運用するのがで、IT技術が世の中に広まった現在は、他からの新製品/新サービスが登場したらそれらの追随する必要がある同じコードを使い続けることは何を意味するのか

## メリット
### 構成管理
- サステナブルという意味で継続的にコードが改善できる状態
- gitなどのツールを使い、コードの差分やコードの分岐に対して作業コストが低く抑えられる
- 運用まで含めたコードに継続的な利用が可能になる仕組みが整えられている
### リファクタリング
- 一度組み合わさって実行されているものを組み直す手法
- 複雑奇怪になってしまったコードを組み直す事も可能
- テスト駆動開発の単体テストと一体にして使い、古いコードから最新のコードに移植する場合も基本的にはリファクタリングの概念が利用できます 

## デメリット
- コードが書きっぱなしになっており、本番環境にしか残ってない
- 目の前で動いているものを組み直した時に、また動くことを保証できない


