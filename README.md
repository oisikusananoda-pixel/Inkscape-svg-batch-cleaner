# Inkscape SVG Batch Cleaner

This tool batch-cleans SVG files created with Inkscape by removing unnecessary metadata and hidden elements.
It is designed to run on **Google Colab** and is useful for preparing SVG files for other applications such as **FontForge**.

---

## Features

* Removes Inkscape and Sodipodi specific metadata
* Deletes editor-only tags such as grids and guides
* Removes hidden elements (`display:none`, `visibility:hidden`)
* Batch processes multiple SVG files at once
* Runs entirely on Google Colab (no local setup required)
* Outputs cleaned SVG files as a ZIP archive

---

## Usage (Google Colab)

1. Prepare a folder containing SVG files created with Inkscape.
2. Compress the folder into a ZIP file.
3. Open this notebook in Google Colab.
4. Run all cells.
5. Upload the ZIP file when prompted.
6. Download the generated `_cleaned.zip` file after processing.

---

## Notes

* Even if the original folder contains non-SVG files, only SVG files will be processed.
* Non-SVG files are automatically excluded from the output ZIP file.
* The visual appearance of the SVG files is not changed.
* Parts of this project were developed with the assistance of AI tools.

---

## Requirements

* Google Colab
* Python 3.x
* `lxml` library

(All dependencies are available by default on Google Colab.)

---

## License

MIT License

---

---

# Inkscape SVG Batch Cleaner（日本語）

このツールは、Inkscapeで作成されたSVGファイルから不要なメタデータや非表示要素を削除し、クリーンなSVGファイルに変換するためのバッチ処理ツールです。
**Google Colab上での実行**を前提としており、**FontForge**など他のアプリケーションで利用する前処理に適しています。

---

## 特徴

* Inkscape / Sodipodi 固有のメタデータを削除
* グリッドやガイドなど編集用タグを削除
* 非表示要素（`display:none`, `visibility:hidden`）を削除
* 複数のSVGファイルを一括処理
* Google Colab上でそのまま実行可能（環境構築不要）
* クリーン化したSVGをZIPファイルとして出力

---

## 使い方（Google Colab）

1. Inkscapeで作成したSVGファイルをフォルダーにまとめます。
2. フォルダーをZIPファイルに圧縮します。
3. このノートブックをGoogle Colabで開きます。
4. すべてのセルを実行します。
5. 指示に従ってZIPファイルをアップロードします。
6. 処理完了後、生成された `_cleaned.zip` をダウンロードします。

---

## 注意事項

* 変換前のフォルダーにSVG以外のファイルが含まれていても、SVGファイルのみが処理されます。
* SVG以外のファイルは出力されるZIPファイルには含まれません。
* SVGの見た目（描画結果）は変更されません。
* このプロジェクトの一部はAIツールを用いて開発されました。
---

## 動作環境

* Google Colab
* Python 3.x
* `lxml` ライブラリ

（Google Colabでは追加のインストールは不要です。）

---

## ライセンス

MIT License
