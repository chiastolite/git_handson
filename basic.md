1. git clone してリモートからファイルを持ってくる
    * SourceTreeで見て、脳内にコミットグラフのイメージを形成する
2. 講師がcommit & push する
3. git fetchする
    * ここではローカルとリモートに差が出ることを意識して欲しいのでpullではなくfetch
    * masterとorigin/masterに差が出ているので同期が必要なことを認識
4. git merge --no-ff
    * fast-forwardしないのはマージをしたというイメージを持ってもらうため
