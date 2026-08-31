# yla-meta

YLA の更新メタデータ（`latest.json` のみ）。アプリが起動時に参照し、新しいバージョンの案内を表示します。

- `app.version` — 最新リリースのバージョン
- `app.downloadUrl` — 配布リンク（空の場合、アプリは「配布元から受け取ってください」と案内）
- `data.version` — チャートデータパックの版（YYYYMMDD）

本体の配布はこのリポジトリでは行いません。
