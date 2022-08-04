# AWS

## 気をつけたほうがいいこと

#### 環境名に大文字を使わない
プロジェクトにおいて、`develop`,`staging`,`production`といった環境を設定するが、環境名に大文字を混入させないほうがいい。<br>
理由は、S3のバケット名に大文字を使うことができないため。リソースの作成・運用面で整合性を取る際に苦労することになる。<br>
[参考:S3の命名規則](https://docs.aws.amazon.com/ja_jp/AmazonS3/latest/userguide/bucketnamingrules.html)