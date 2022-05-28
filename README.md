# nekome

A new Flutter project.

## 開発流れ

1 issueを立てる

2 branchを切る `git checkout -b feature/#issue番号_new_branch`

3 作業をする

4 適宜コミットする `git commit -m [add] #1 top画面の作成`

- fix: バグ修正
- add: 新規（ファイル）機能追加
- update: 機能修正(バグではない）
- remove: 削除（ファイル）


5 featureのremote branchにpush `git push origin feature/#issue番号_new_branch`

6 pull request(マージリクエスト）を行う

7 review　＆　リファクタリング

8 マージ

9 remoteの変更をlocalに反映 `git checkout main `   `git pull`

1 issueを立てる....


## ディレクトリ構成
```
lib
 L data
   L controller
   L models
   L repository
 L ui
   L route
   L store
   L worker
```

