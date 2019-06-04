# gitbootcamp20190604

# 1.git addコマンド

　以下のコマンドを実施し、ステージングエリアにファイルを追加します。

    git add [ファイル名]

# 2.git commit
  1. 追加・変更したファイルをGitに登録するためのコマンド
  1. commitしない限りレポジトリには反映されない

# 3.git commit -a　とは
  1. このオプションにより、作業ツリーで変更されたか削除されたファイルを自動的にインデックスにステージしてコミットができる。  
  1. これによりgit addを実行することになくコミットできます

# 4.git commit --amend

前回のコミットログを修正したい！と思った時には以下のコマンドを利用します。

    git commit --amend

# 5.git branch fix/42
  1. "fix/42"ブランチを生成するコマンド
  1. HEADはmasterに留まったまま
  1. このブランチを使用することで、同時並行で開発を行うことができるため　バグ修正や新機能開発などの場面で使用できる

# 7.git checkout -b
  1. 「-b」オプションを指定することで、ブランチの作成とチェックアウトを同時に行うことができます。

# 8.git reset --hard master
  1. ブランチをmasterへ強制的にリセットして、ブランチの変更を破棄する
  1. HEADもそのコミットへ移動する
  1. 破棄したブランチはgcで2週間で削除される

# 9.git mearge fix/42
  1. 現在のブランチ(HEADの指している場所)へ、他のブランチの更新を取り込む処理

# 10.git rebase -i

オプションをつけると、「interactiveモード」なリベースがおこなえます。

    git rebase -i [コミット]

# 12.git checkout fix/42

ブランチを変更する場合に以下のコマンドを利用します。

    git checkout [ブランチ名]


# 14.git merge --ff-only fix/42
  1. ファーストフォワード可能な場合に、現在のHEADのmasterをfix/42まで進めるためのコマンド
  1. ブランチがフィードフォワードができない状態ではエラーとなる

# 15.git merge -no-ff fix/42
  1. マージする二つのブランチがfast-forwardな関係であってもそうでなくても、必ずマージコミットが作られる。


# 17.git remote add; git fetch --all
  1. リモートAで作業しているときにリモートBの内容をマージしたいときに仕様するコマンド
  1. リモートBをaddし、その内容をすべてフェッチすることでローカルのレポジトリに内容を取り込む

# 20.git push
  1. ローカルの変更内容をリモートに反映する

# 23.git clone
リモートレポジトリをローカルの指定したディレクトに複製するコマンド。
ローカルレポジトリをコピーすることもできる

    git clone [クローンしたいリポジトリ] [クローン先のディレクトリ(省略可)]

##ブランチを作成しました。
##ブランチを作成しました。2回目
