# nomukoh.github.io

個人用のホームページです。

## 公開構成

- ルート: `index.html`

公開 URL（プロジェクトページ）:

- <https://nomukoh.github.io/>

## GitHub Pages 設定

GitHub リポジトリの `Settings` -> `Pages` で以下を設定

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

## ローカル確認

[git clone + poetry の環境構築方法](https://qiita.com/nomukoh/items/bb08de2405c1500100c3)

例（Python）:

```bash
python -m http.server 8000
```

その後、`http://localhost:8000/` を開いて表示を確認
