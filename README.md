# JOJO NEWS 公式リンク集

Xアカウント「JOJO NEWS」で紹介したジョジョ／荒木飛呂彦関連情報の、公式サイト・公式Xなどへの公開リンク集です。

## 公開データ

- `index.html`: GitHub Pages用の表示ページ
- `data/news.json`: 掲載データ

`data/news.json` の形式:

```json
{
  "updated_at": "2026-10-01",
  "items": [
    {
      "date": "2026-10-01",
      "category": "グッズ",
      "title": "ニュースタイトル",
      "source_type": "公式サイト",
      "url": "https://example.com/",
      "note": "任意の補足"
    }
  ]
}
```

BOT本体・APIキー・ログ・管理用データはこの公開リポジトリには保存しません。
