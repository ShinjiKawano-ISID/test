# SourceTreeのインストール

## Atlassian accountの作成

ブラウザで[https://id.atlassian.com/signup](https://id.atlassian.com/signup)ヘアクセスします。

「メールアドレス」「氏名」「パスワード」を入力し、「Sign Up」を選択します。メールアドレスは会社のアドレスを使用して下さい。

![01](./img/environment/atlassian_account/01.png)

会社のメールアドレス宛にAtlassianから確認メールが届いていることを確認して下さい。

## SourceTreeのインストール

SourceTreeをインストールします(以下では2019/03/01時点での最新バージョンであるSourceTree3.0.17を使用しています)。

インストーラーを起動します。

ウィザードに従ってインストールを進めます。右のBitbucket(Bitbucket Cloud)を選択します。

![01](./img/environment/install_sourcetree/01.png)

Bitbucketを選択すると、別ウィンドウが開きます。お好きなユーザ名を入力して「続行」してください。インストーラに戻ると、次に進みます。

![02](./img/environment/install_sourcetree/02.png)

![03](./img/environment/install_sourcetree/03.png)

Gitが「Not Install」となっている場合は、チェックを入れて「次へ」を押します。

![04](./img/environment/install_sourcetree/04.png)

特に何もチェック、入力しない状態で次に行ってもらって構いません。

![05](./img/environment/install_sourcetree/05.png)


「SSHキーを読み込みますか？」というダイアログが出るので、「No」を選択します。

![06](./img/environment/install_sourcetree/06.png)

SourceTreeが起動します。

![07](./img/environment/install_sourcetree/07.png)

続いてユーザーの名前とメールアドレスを設定します。

「ツール」の「オプション」を選択します。「全般」タブの「デフォルトユーザー情報」に、各自の名前とメールアドレスを入力し、OKを押します。

![08](./img/environment/install_sourcetree/08.png)

「ネットワーク」タブを開き、下図の通りプロキシ設定を入力し、OKを押します。

![09](./img/environment/install_sourcetree/09.png)

「Git」タブを開き、下図の通りGitが有効になっていることを確認して下さい。
（Gitバージョンやチェックボックスの内容は実際と異なる場合があります）

![10](./img/environment/install_sourcetree/10.png)

「Gitサポートは現在無効です」と表示される場合は、「Gitサポートを有効化」を押下し、
「システム全体でなく、SourceTree単独で使うためだけの内臓のGitを～」を選択してください。

以上でSourceTreeのインストールは完了です。
