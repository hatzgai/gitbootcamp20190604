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

## 1.git addコマンド

　以下のコマンドを実施し、ステージングエリアにファイルを追加します。

    git add [ファイル名]

## 4.git commit --amend

前回のコミットログを修正したい！と思った時には以下のコマンドを利用します。

    git commit --amend

## 7.git checkout fix/42

ブランチを変更する場合に以下のコマンドを利用します。

    git checkout [ブランチ名]

## 10.git rebase -i

オプションをつけると、「interactiveモード」なリベースがおこなえます。

    git rebase -i [コミット]
