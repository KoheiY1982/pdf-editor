# PDF Editor Local

ブラウザで動作するオフラインPDF編集ツール。インストール不要。

## 使い方

`index.html` をダブルクリックして開くだけ。

## 機能

- ページのサムネイル表示・プレビュー
- ページの削除・回転・並び替え（ドラッグ＆ドロップ）
- 複数PDFの結合
- ページ分割
- 圧縮
- 名前を付けて保存（Windowsネイティブダイアログ）

## 必要ファイル

```
pdf-editor/
├── index.html
├── pdf-lib.min.js
├── pdf.min.js
└── pdf.worker.min.js
```

4ファイルを同じフォルダに置いて使用。

## 技術スタック

- [PDF-lib](https://pdf-lib.js.org/) — PDF編集
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDFレンダリング
- バニラJS / HTML / CSS

## 動作環境

Chrome / Edge 最新版（ローカルファイルとして開く）
