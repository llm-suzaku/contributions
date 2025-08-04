# Contributions
このページは、チーム朱雀のgithub学習用、共有ソースコード置き場として
first-contributionsのページを改変して作成しました。  
https://github.com/firstcontributions/first-contributions

# 注意
本ページの、TeamMembers.md、srcディレクトリ直下は、プルリクと同時に(レビュー無しで)レポジトリにマージするように設定しています。
他メンバーのソースコードの改変などは、決して許可なく行わないようにご注意ください。


<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />


## リポジトリをフォーク

Forkボタンをクリックしてこのリポジトリをフォークしてください。
この作業であなたのアカウントにはこのリポジトリのコピーが作られます。

## リポジトリをクローン

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

次にフォークしたリポジトリをクローンします。あなたのリポジトリに移動してフォークしたリポジトリを開き*Code*ボタンをクリックした後に*Copy to clipboard*アイコンをクリックしてください。

ターミナルを開いて以下のgitコマンドを実行してください：

```
git clone "コピーしたURL"
```
"コピーしたURL" (ダブルクオーテーションは除いてください) は先ほどコピーしたリポジトリのURLと置き換えてください。

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

例：
```
git clone https://github.com/＜あなたのユーザー名＞/contributions.git
```
`あなたのユーザー名` はご自身のGitHubユーザー名に置き換えてください。この作業でGitHub のリポジトリの内容はあなたのコンピュータに保存されました。

## ブランチを作成

もしリポジトリのディレクトリにいなければそこまで移動してください。

```
cd contributions
```
`git switch` コマンドを使用してブランチを作成します：
```
git switch -c <add-your-name>
```

例:
```
git switch -c add-alonzo-church
```
(ブランチの名前には必ずしも*add*が含まれていなければならないわけではありませんが、このブランチの目的があなたの名前をリストに加えることであることを考慮すれば含むのが適切です。)

## コードを変更してその変更をコミット

テキストエディタで`TeamMembers.md`ファイルを開いてあなたの名前を追記してください。  
ファイルの先頭または最後に追加しないようにしましょう。  
名前リストの間のどこか好きな場所に、あなたの名前を追加するようにしてください。  
あなたの名前をファイルに加えたら、ファイルを保存します。
名前の追記は、  
あなたのSlack名(あなたのgithubのページ)  
で追記しましょう。
![alt text](/image/image-3.png)

プロジェクトディレクトリに移動して`git status`を実行すると、変更がなされたことが確認できると思います。`git add`コマンドを使ってそれらの変更を適用してください。
```
git add TeamMembers.md
```

次に`git commit`コマンドを使ってこれらの変更をコミットします。
```
git commit -m "Add <あなたの名前> to TeamMembers list"
```
`<あなたの名前>`をご自身の名前に置き換えてください。

## GitHubに変更をpushする

`git push`コマンドを使って変更をpushしてください。
```
git push origin <ブランチ名>
```
`<ブランチ名>`には先ほど作成したブランチ名を入れてください。

## レビューのためにプルリクエストを送る

GitHub上であなたのリポジトリに行くと、`Compare & pull request`ボタンが表示されます。そのボタンをクリックしてください。
![alt text](/image/image-4.png)


プルリクエストを作ってください。
![alt text](/image/image-5.png)


すぐに変更がこのプロジェクトのmainブランチにマージされます。マージが終了した際にはその旨のメールが送られます。

## 同様に、srcディレクトリ内に自身のディレクトリを作成して、ソースコードをアップロードしてください。




このプロジェクトは firstcontributions/first-contributions（MITライセンス）を参考にしています。  
[Copyright (c) firstcontributions/first-contributions]  
このソースコードはMITライセンスの下で提供されています。
