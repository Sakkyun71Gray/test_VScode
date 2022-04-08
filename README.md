# test_VScode

## VScodeとの連携を確認するリポジトリ

<br>

### 資格情報の削除(これをすることで複数のアカウントの切り替えが容易となる)
`cmdkey /delete:git:https://github.com`

<br>

### 参考URL
[VScodeとGitHubの連携](https://breezegroup.co.jp/202102/vscode-github-windows/?msclkid=ca6daf56b6db11ec8cdd5e6bbb67115c)

[GitHubのアカウント連携](https://qiita.com/tn_movie/items/5dee0092704cd28ed85c?msclkid=ba71b905b6dc11ec83acef5e083c511f)

[GitHubユーザの切り替え](https://wood-roots.com/web/tool-editor/2553?msclkid=43daad23b6ed11eca62a1a1cc1606740)

[ユーザ・ワークスペース・フォルダの設定の違い](https://creating-homepage.com/archives/9365)

[READMEの書き方](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

<br>

### README確認
<br>

#### ・コードの挿入
```
public class Hello_VScode {
    public static void main(String[] args) {
        System.out.println("Hello, VScode!");
        System.out.println("Hello, GitHub!");
        System.out.println("Change directory");
        System.out.println("relogin the account");
    }
}
```
<br>

#### ・表の挿入
| テスト | テスト | テスト |
| ------ | ------ | ------ |
| 1      | 2      | 3      |
| 4      | 5      | 6      |
| 7      | 8      | 9      |
