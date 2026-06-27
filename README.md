# 思考醸造所

アイデアを預けて、忘れる。思考を醸造するファストメモ（単一HTML・localStorage・PWA）。

- 公開URL: https://sodustry.github.io/brewery/
- iPhone: Safari で開く → 共有 →「ホーム画面に追加」でアプリのように使えます（オフライン対応）。

## 構成
- `index.html` — 本体（localStorage に保存。サーバー不要）
- `manifest.webmanifest` / `sw.js` — PWA（インストール・オフライン）
- `icon-*.png` / `favicon.png` — アイコン

すべて相対パスなので、GitHub Pages のサブパス配信でそのまま動作します。
