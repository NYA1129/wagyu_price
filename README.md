# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

### リモートリポジトリ：GitHubのような、ネットワーク上のサーバにあるリポジトリ。
### ローカルリポジトリ：個人のPC内にあるリポジトリ。

## プッシュとマージの違いは何でしょうか？

### プッシュの「ローカルリポジトリの変更内容を同じブランチのリモートリポジトリに反映させること」に対し、
### マージは「masterブランチに他のブランチの変更内容を反映させること」。

## コミットとプッシュの違い

### コミットは変更内容をローカルリポジトリに反映させることで、プッシュは変更内容をリモートリポジトリに反映させること。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

### 変更内容一目でわかるように書く。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

### ローカルでマージするフローに比べて、プルリクエストでマージするフローはマージするためにレビュー担当者の承認が必要となるため事前にバグを回避することができる。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

### 下記のいずれかの方法で対処できる。
#### 先にマージされた変更内容を取り込む
#### 後にマージしようとしている変更内容を取り込む
#### どちらの変更内容も取り込む

### しかしいずれの方法にせよ、少しでも意図のわからないほかの人が行った変更に対処するときはそのソースコードを書いた人と相談しながら作業をする必要がある。