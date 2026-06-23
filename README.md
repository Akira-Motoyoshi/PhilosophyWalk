# PhilosophyWalk

OSM `relation/18344117`（哲学の道 / Philosopher's Walk）周辺の橋名タグを確認するための監査資料です。

## Files

- `reports/philosophers_walk_bridge_name_audit.xlsx`
  - OSMから抽出した `bridge=*` wayの候補一覧、言語別タグ有無、手動確認用メモをまとめたスプレッドシート。
- `reports/philosophers_walk_bridge_name_audit_explainer.docx`
  - スプレッドシート作成時に行ったこと、判定ロジック、見方、人手ダブルチェック方法をまとめた解説資料。

## Notes

- 対象は `way/18344117` ではなく `relation/18344117` です。
- 主候補は relation から80m以内の `bridge=*` wayです。
- スプレッドシートはAI翻訳を追加するものではなく、OSM上に既存の多言語タグがあるかを監査するためのものです。
- 精度優先のため、OSM編集前に人手で対象範囲・橋名・翻訳名の妥当性を確認してください。
