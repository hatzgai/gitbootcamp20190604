# gitbootcamp20190604

# git commit -a　とは
  1. このオプションにより、作業ツリーで変更されたか削除されたファイルを自動的にインデックスにステージしてコミットができる。  
  1. これによりgit addを実行することになくコミットできます。

# git checkout -b
  1. 「-b」オプションを指定することで、ブランチの作成とチェックアウトを同時に行うことができます。

# git checkout fix/42
  1. 作成したブランチで作業をするにはチェックアウト(checkout)コマンドでブランチを切り替える必要があります。

# gti commit -a　とは
  1. このオプションにより、作業ツリーで変更されたか削除されたファイルを自動的にインデックスにステージしてコミットができる。  
  1. これによりgit addを実行することになくコミットできます。

## git addコマンド

　以下のコマンドを実施し、ステージングエリアにファイルを追加します。

    git add [ファイル名]

## git commit --amend

前回のコミットログを修正したい！と思った時には以下のコマンドを利用します。

    git commit --amend

## git checkout fix/42

ブランチを変更する場合に以下のコマンドを利用します。

    git checkout [ブランチ名]

## git rebase -i

オプションをつけると、「interactiveモード」なリベースがおこなえます。

    git rebase -i [コミット]

## git commit
1.追加・変更したファイルをGitに登録するためのコマンド
1.commitしない限りレポジトリには反映されない

## gti commit -a　とは
1.このオプションにより、作業ツリーで変更されたか削除されたファイルを自動的にインデックスにステージしてコミットができる。  
1.これによりgit addを実行することになくコミットできます

## git branch fix/42
1."fix/42"ブランチを生成するコマンド
1.HEADはmasterに留まったまま
1.このブランチを使用することで、同時並行で開発を行うことができるため
　バグ修正や新機能開発などの場面で使用できる

## git reset --hard master
1.ブランチをmasterへ強制的にリセットして、ブランチの変更を破棄する
1.HEADもそのコミットへ移動する
1.破棄したブランチはgcで2週間で削除される

## コミット、ステージ済みコミット

## git merge --ff-only fix/42
1.ファーストフォワード可能な場合に、現在のHEADのmasterをfix/42まで進めるためのコマンド
1.ブランチがフィードフォワードができない状態ではエラーとなる

## git remote add; git fetch --all
1.リモートAで作業しているときにリモートBの内容をマージしたいときに仕様するコマンド
1.リモートBをaddし、その内容をすべてフェッチすることでローカルのレポジトリに内容を取り込む

## git push
1.ローカルの変更内容をリモートに反映する

23. git clone
・リモートレポジトリをローカルの指定したディレクトに複製するコマンド
・ローカルレポジトリをコピーすることもできる

##ブランチを作成しました。
##ブランチを作成しました。2回目

## git clone
1.リモートレポジトリをローカルの指定したディレクトに複製するコマンド

## git clone
1.リモートレポジトリをローカルの指定したディレクトに複製するコマンド
1.ローカルレポジトリをコピーすることもできる
