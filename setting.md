初期設定
===

## ユーザー情報の登録

```
git config --global user.name  'Your Name'
git config --global user.email 'Your Address'
```

## 改行コードの取扱についての設定

Gitではファイルを保存する際に改行コードについての処理を行いません
全員のプラットフォームが統一されていれば問題はないのですが
あとから別の人が入ったときに困らないようにLFで統一して保存するようにします

設定項目の詳細に関しては割愛しますので、各自ぐぐるかRedmineの知識DBに記事を書いてありますので、そちらを見てください

### macの人

```
git config --global core.autocrlf input
git config --global core.safecrlf true
```

### winの人

```
git config --global core.autocrlf true
git config --global core.safecrlf true
```
