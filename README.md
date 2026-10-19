# JOJO NEWS 公式リンク集

Xアカウント「JOJO NEWS」で紹介したジョジョ／荒木飛呂彦関連情報の、公式サイト・公式Xなどへの公開リンク集です。

## 公開データ

- `index.html`: GitHub Pages用の表示ページ
- `data/news.json`: 掲載データ
- `data/goods.json`: グッズ掲載データ

詳細一覧には、週報に掲載する行をX投稿URLの有無にかかわらず掲載します。
`url` が空の行は一覧には表示しますが、タイトル左のXアイコン（元ポストへのリンク）は表示しません。

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

`url` は任意です。X投稿がない項目は空文字でも掲載対象とします。

BOT本体・APIキー・ログ・管理用データはこの公開リポジトリには保存しません。