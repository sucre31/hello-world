#gitコマンドのまとめ

1.基本
- git init
    - gitの初期化
- git status
    - ワークツリーのステータスを表示
- git config
    - 設定の確認・変更
- git log
    - ログ表示
- git diff
    - ファイルの差分を表示

2.コミット系
- git add
    - ステージングエリアに追加
- git commit
    - コミットの実行
    - git commit -m "コメント内容" でコメントを追加

3.修正系
- git commit --amend --no-edit
    - コミットの修正
- git checkout
    - 過去コミットの復旧など
- git reset
    - コミットのリセット
- git revert
    - コミットの変更を打ち消すコミット
- git rm
    - ファイルとindex情報の削除

4.共同編集
- git stash
    - 一時退避
- git pull
    - originからプル
- git stash pop
    - 一時退避したものの変更を加える
- git diff origin index.html
    - originとローカルのファイルの比較
- git merge --abort
    - mainブランチをマージ前に復元
- git reset --hard
    - マージを開始する前の状態に戻す