# niche-sites

ニッチ特化サイト量産プログラムの共通リポジトリ。各サイトは sites/<slug>/ に静的サイト一式（dist）を置き、Vercelプロジェクトごとに Root Directory をそのフォルダに指定して公開する。

- 公開済み: 食PRポストは単独リポジトリ yukishibue-bot/food-pr-post で運用（このリポジトリには含まない）
- 新規サイトの必須ファイル: ルートに IndexNow キーファイル `52ca2b226af3164718fcf3987444e006.txt`（中身はキー文字列そのもの）を置くこと。公開後は indexnow_client.py で更新URLを即時通知する運用（詳細は ~/workspace/api-connectors/SETUP-PLAN.md の横断設計）。
