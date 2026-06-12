# api-setup-practice

## 概要
Laravel Tutorial API開発環境の構築と疎通確認

## 使用技術
- PHP 8.x
- Laravel 10.x
- REST API (JSONレスポンス)
- Postman, curl (動作確認)

## 学んだこと
- LaravelでのAPIの作成方法
- API開発においては `web.php` ではなく `api.php` にルートを設定する
- `api.php` にルートを設定すると、自動的にパスにプリフィックスが付与される（デフォルトでは `/api`）

## 動作確認
`http://localhost/api/hello` にGETリクエストを送信し、ステータスコード `200` と `{ "message": "Hello, API!"}` が返ってくる
