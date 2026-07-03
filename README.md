# sansan-competition

Google Classroom運用支援AIエージェントのGUIプロトタイプです。

## 起動

```bash
python3 main.py --port 8000
```

ブラウザで `http://127.0.0.1:8000` を開きます。

## 現在の実装範囲

- Googleログイン画面のモック
- コース選択
- ダッシュボード
- 課題詳細と提出状況表示
- AIアウトプットJSONのカード、表、警告、編集フィールド表示
- 出力形式選択
- Classroom投稿前の承認画面

Google OAuth、Classroom API、AI生成処理、実際のPDF/Markdown/Google Document出力は未接続です。
