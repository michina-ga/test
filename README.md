 マークダウンでREADMEをつくる
gitからのclone
```
git clone https://github.com/michina-ga/test
```
アポストロフィ三つでプログラムのように整形される


branchは別の世界線みたいなもの
新しいbranchを作った場合, 作成時点の世界を複製している
新しいbranchに変更を追加した場合, 元のbranch(masterなど)には反映されずに維持できる
新しい世界線としてpushもできる
branchの確認
```
git branch
```
branchの作成
```
git branch branch_name
```
branchへの移動
```
git checkout branch_name
```
branchの削除(削除対象のbranchの外から実行)
ローカルbranchの削除
```
git branch -D branch_name
```
branchの統合(ローカル内での作業)(統合先のbranch内から実行)
```
git merge branch_name
```
branchの統合内容をpush
```
git push -u origin master
```
