# STRiGHT CMP - Google Tag Manager Template

STRiGHT ONEのクッキー同意管理ツールをGoogle Tag Manager経由でウェブサイトに導入し、Google Consent Mode v2とシームレスに連携できるテンプレートです。

## Setup / 設定方法

1. GTMにアクセスし、サイドバーの「タグ」を選択してください。
2. 「新規」>「タグの設定」を選択してください。
3. 「コミュニティテンプレートギャラリーでタグタイプをさらに見つけましょう」を選択してください。
4. 検索欄で「STRiGHT CMP」を検索し、テンプレートを追加してください。
5. 各種値を入力してください。
6. トリガーに「Consent Initialization - All Pages」（同意の初期化）を選択してください。

## Parameters / パラメータ

| Parameter | Description |
|---|---|
| サイトID | STRiGHT ONEのサイトID（`SIT-xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx`） |
| スクリプトURL | スクリプトの配信元URL |
| Google同意モード | Google Consent Mode v2 の利用有無 |
| Google同意モードの設定 | カテゴリごとの同意モデル（オプトイン / オプトアウト / 常に許可 / 常に拒否） |
| リージョン別Google同意モードの設定 | リージョンコードごとの同意状態の上書き |
| サイトドメイン | Cookie照合用のサイトドメイン |

## Google Consent Mode v2

Google同意モードを「利用する」に設定すると、以下のカテゴリとGoogle Consent Modeキーが連携されます。

| Category | GCM Keys |
|---|---|
| アクセス解析 | `analytics_storage` |
| 機能性拡張 | `functionality_storage`, `personalization_storage` |
| 広告・マーケティング | `ad_storage`, `ad_user_data`, `ad_personalization` |
| 個人データ紐づけ | `security_storage` |

## ライセンス

本プロジェクトは [Apache License 2.0](LICENSE) のもとで公開されています。

Copyright 2024 Internet Initiative Japan Inc.
