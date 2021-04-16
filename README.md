# git環境の構築並びにgithubCLIの設定

## 環境
- OS Windows10
- VScodeがインストールされている

## 手順
- 1, https://git-scm.com/downloads からgitをダウンロードする。
- 2, 基本的には全てもとから入っているチェックマークのままでよいが以下に示す物だけは変更する

![Image 1](images/3.jpg)
![Image 1](images/5.jpg)

- 3, https://cli.github.com/ からgithubCLIをダウンロードする。（これはダウンローダーの指示に従うだけで良い）
- 4, コマンドプロンプトを起動し　$ gh auth login を実行
- 5, その後対話的に処理を実行し認証を行う（分からない場合にはgh auth login 手順などで調べるといろいろと出てくるのでそれらを参考に...）


これで基本的な設定は終了しgitならびにghコマンドが使えるようになります。

細かい点は気が向いたら追記するかも？
