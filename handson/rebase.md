* number.txtの編集
 * 適当な数字の後に記号を書いたり消したり
 * すでにある記号を消したり置き換えてもよい
* git add; git commitでローカルにコミット
 * コミットメッセージもちゃんと書くこと
* git pushでGitHubへ
* git pull --rebase で他のチームの変更を取り込む
 * GitHub公式クライアントを使う場合はSync
 * 競合が起きたら修正してください
  * 修正が終わったら git rebase --continue
  * git commitをしてはいけません
* 各チームが5回コミットしたら終了
* GitHubのNetworkで確認しましょう
 * git log --graph --pretty=oneline でも可
