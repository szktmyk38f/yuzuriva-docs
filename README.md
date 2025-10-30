# ユズリバ - 公式ドキュメント

このディレクトリには、ユズリバアプリの公式Webページが含まれています。

## 公開ページ

- **トップページ**: [index.html](index.html)
- **プライバシーポリシー**: [privacy-policy.html](privacy-policy.html)
- **サポート**: [support.html](support.html)

## GitHub Pages設定

このディレクトリは、GitHub Pagesを使用して公開されます。

### 設定手順

1. GitHubリポジトリの「Settings」を開く
2. 「Pages」セクションに移動
3. 「Source」で「Deploy from a branch」を選択
4. 「Branch」で `main` ブランチと `/docs` フォルダを選択
5. 「Save」をクリック

### 公開URL

GitHub Pagesが有効化されると、以下のURLでアクセス可能になります：

- `https://<username>.github.io/<repository>/`
- プライバシーポリシー: `https://<username>.github.io/<repository>/privacy-policy.html`
- サポート: `https://<username>.github.io/<repository>/support.html`

## ファイル構成

```
docs/
├── .nojekyll          # Jekyll無効化
├── README.md          # このファイル
├── index.html         # トップページ
├── privacy-policy.html # プライバシーポリシー
└── support.html       # サポートページ
```

## 更新方法

HTMLファイルを直接編集して、GitHubにプッシュするだけで自動的に更新されます。

## 注意事項

- すべてのHTMLファイルは日本語で記載されています
- レスポンシブデザインに対応しています
- 外部ライブラリは使用していません（純粋なHTML/CSS）
