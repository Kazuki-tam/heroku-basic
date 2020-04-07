# Herokuベーシック認証テンプレート
Herokuに静的ファイルをアップロードしてベーシック認証を設定するテンプレートです。
`.htpasswd` に指定したいID, Passを入力してHerokuへデプロイします。
デプロイするルートディレクトリ直下に以下ファイル一式を格納して利用します。

- `.htaccess`
- `.htaccess`
- `composer.json`
- `index.php`

以下ツールでID, Passを暗号化させて利用してください。
[.htaccess による認証用パスワード暗号化ツール](https://www.luft.co.jp/cgi/htpasswd.php)