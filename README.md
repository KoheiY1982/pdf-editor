# Local Editor Tools

ブラウザで動作するオフライン編集ツール集。インストール不要。

## ツール一覧

### 📄 PDF Editor (`pdf-editor.html`)
- ページのサムネイル表示・プレビュー
- ページの削除・回転・並び替え（ドラッグ＆ドロップ）
- 複数PDFの結合
- ページ分割
- 圧縮
- 名前を付けて保存（Windowsネイティブダイアログ）

### 🖼️ Image Editor (`image-editor.html`)
- JPG / PNG / WEBP / GIF の読み込み
- 回転・並び替え・削除
- 回転済みJPGとして個別保存
- 複数画像を1つのPDFに変換・結合

## 使い方

`index.html` をブラウザで開くとハブページが表示されます。

## ファイル構成

```
├── index.html          # ハブページ
├── pdf-editor.html     # PDF Editor
├── image-editor.html   # Image Editor
├── pdf-lib.min.js      # PDF-lib（PDF操作）
├── pdf.min.js          # PDF.js（PDFレンダリング）
└── pdf.worker.min.js   # PDF.js Worker
```

## 技術スタック

- [PDF-lib](https://pdf-lib.js.org/) — PDF編集・生成
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDFレンダリング
- Canvas 2D API — 画像回転処理
- バニラJS / HTML / CSS（外部依存なし）

## 動作環境

Chrome / Edge 最新版（ローカルファイルとして開く）
