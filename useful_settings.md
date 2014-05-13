社内ネットワークとの兼ね合い
===

Gitでは外部ネットワークとのやりとりをするプロトコルとして、git,https,sshが使えます。
このうちgitプロトコルのポートは閉じられているため、https、sshのどちらかを使うしかありません。

ライブラリなどによってはgitプロトコルをデフォルトとしているものもあるので、設定で強制的にhttps/sshを使うようにする必要があります。

### httpsを使う

```
git config --global url.https://github.com/.insteadOf https://github.com/
```

### sshを使う

~/.gitconfigに以下の内容を追記

```
[url "git@github.com:"]
   insteadOf = git://github.com/
   insteadOf = https://github.com
```
