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

    git add [ファイル市]

## 4.git commit --amend

前回のコミットログを修正したい！と思った時には以下のコマンドを利用します。

    git commit --amend

## 7.git checkout fix/42

ブランチを変更する場合に以下のコマンドを利用します。

    git checkout [ブランチ名]

## 10.git rebase -i

オプションをつけると、「interactiveモード」なリベースがおこなえます。

    git rebase -i [コミット]

2. git commit
・追加・変更したファイルをGitに登録するためのコマンド
・commitしない限りレポジトリには反映されない

3. gti commit -a　とは
・このオプションにより、作業ツリーで変更されたか削除されたファイルを自動的にインデックスにステージしてコミットができる。  
・これによりgit addを実行することになくコミットできます

5. git branch fix/42
・"fix/42"ブランチを生成するコマンド
・HEADはmasterに留まったまま
・このブランチを使用することで、同時並行で開発を行うことができるため
　バグ修正や新機能開発などの場面で使用できる

8. git reset --hard master
・ブランチをmasterへ強制的にリセットして、ブランチの変更を破棄する
・HEADもそのコミットへ移動する
・破棄したブランチはgcで2週間で削除される

#git mearge fix/42
 現在のブランチ(HEADの指している場所)へ、他のブランチの更新を取り込む処理

11. コミット、ステージ済みコミット

14. git merge --ff-only fix/42
・ファーストフォワード可能な場合に、現在のHEADのmasterをfix/42まで進めるためのコマンド
・ブランチがフィードフォワードができない状態ではエラーとなる

17. git remote add; git fetch --all
・リモートAで作業しているときにリモートBの内容をマージしたいときに仕様するコマンド
・リモートBをaddし、その内容をすべてフェッチすることでローカルのレポジトリに内容を取り込む

20. git push
・ローカルの変更内容をリモートに反映する

23. git clone
・リモートレポジトリをローカルの指定したディレクトに複製するコマンド
・ローカルレポジトリをコピーすることもできる


#git merge -no-ff fix/42
 マージする二つのブランチがfast-forwardな関係であってもそうでなくても、必ずマージコミットが作られる。