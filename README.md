



## Git基本操作

- どこかに適当なフォルダを作って`git init`でgit管理を始める

- `README.md`を作って`git add README.md`でステージングエリアに移動する

- `git status`でディレクトリの状態を確認する

- `git commit -m first commit`でコミットする

- `git log`でコミットの履歴を見る



- `git reset --hard HEAD`変更内容を取り消して直前のコミットに戻す

- `git reset --hard [コミットID]`で過去のコミットに戻り、それ以降の変更を無かったことにする

- `git revert [コミットID]`で過去のコミットの変更内容を打ち消す

  

- `git stash`で変更内容を一時退避

- `git stash list`で退避リストを表示

- `git stash pop [stash id]`で退避した内容を戻す

  

#### 参考

- [-【初心者向け】Gitってなに？①まず流れを理解する（コードなし） \- Qiita](https://qiita.com/nutsinshell/items/96cb83aecf9d09a7a8bc)

- [基本的なGitコマンドまとめ \- Qiita](https://qiita.com/2m1tsu3/items/6d49374230afab251337)

- [VSCodeでのGitの基本操作まとめ \- Qiita](https://qiita.com/y-tsutsu/items/2ba96b16b220fb5913be)

- [戻したい時よく使っているコマンドまとめ \- Qiita](https://qiita.com/rch1223/items/9377446c3d010d91399b)

  



## ブランチ

・`git branch [ブランチ名]`でブランチを切ってみる

・`git branch`でブランチの一覧を確認する

・`git checkout [ブランチ名]`でブランチを移動する

・`git checkout master`でマスターブランチに戻って`git merge [ブランチ名]`でマージする

・ブランチモデルGit-flow、GitHub-flow、Gitlab-flowについて把握する



- [Gitブランチ関連コマンド \- Qiita](https://qiita.com/ayakix/items/55dc4a324a49ff200c2d)

- [【図解】git\-flow、GitHub Flowを開発現場で使い始めるためにこれだけは覚えておこう：こっそり始めるGit／GitHub超入門（終） \- ＠IT](https://www.atmarkit.co.jp/ait/articles/1708/01/news015.html)



## GitHub

- [GitHub](https://github.com)にリモートリポジトリを作る 

- `git remote add origin [リポジトリURL]`でリモートを追加する

- リモートリポジトリにPushしてみる`git push -u origin master`



プロジェクトに貢献する

- 他の人のリポジトリを`フォーク`して、自分のアカウントにコピーする
- `git clone [リポジトリURL]`でローカルPCにクローンして開発を進める
- `git push `で変更内容を自分のリポジトリに反映させる
- オリジナルのリポジトリにプルリクエストを送ってマージしてもらう



ソーシャル

- [リポジトリをwatchする](https://help.github.com/ja/articles/watching-and-unwatching-repositories)

- [開発者をフォローする](https://help.github.com/ja/articles/following-people)

- 気に入ったリポジトリにStarをつける



#### 参考

[git pull と fetch の違いって何？ \| WWWクリエイターズ](http://www-creators.com/archives/5268)

[GitHub のフォーク （fork） とプルリクエスト （pull request） の使い方 \- akihiro kamijo](http://cuaoar.jp/2013/03/github-fork-pull-request.html)



## プルリクエスト

・`git push origin [ブランチ名]`でリモートにブランチをpushする

・GitHubで`Pull Request`を作成

・レヴュワーに`merge`してもらう

・マージ結果をpullする

[Gitを使ってPull Requestを投げるまで \- Qiita](https://qiita.com/takamii228/items/80c0996a0b5fa39337bd)



## イシュー

- Issueを作ってみる

- Assigneeで担当者を割り振る

- Milestoneで期日を指定する



[チーム開発を変える「GitHub」とは？〜Issuesの使い方〜【連載第3回】 \| SELECK](https://seleck.cc/647)



## プロジェクト管理



## Pages



## Webhooks

## Actions

