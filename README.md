# Gittest

このファイルに名前を追加して、git pushする流れまでを体験しましょう。
`git clone (with SSH)`でこのRepositoryをローカル環境にコピーします。
ローカル環境には、予めgittestというようなRepositoryを作ってその中にコピーしましょう。

## コピーできたら

issueを作ります。
実務者になると、より詳細な内容を書かなければならないですが、今回はテストなので簡潔にissueを作ってOKです。

## issueを作れたら

このREADME.mdをテキストエディタで編集しましょう。

このファイルの一番下に名前とチェックボックスを作製して、保存します。

その後は
作業用のブランチを作製します。
まず、git branchで現在のbranchは何かを確認します。

その後、

`git checkout -b chore/111_test_....`
というような形で作業用のブランチを作ります。

`git add .`

`git commit`

`git push origin master`

という過程を取ってファイルをリモートRepositoryにあげましょう。

## Name

- [x] Takuya Yamamoto
- [x] Yukako Nishimura
