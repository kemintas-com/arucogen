# arucogen

Single-file ArUco marker generator for OpenCV-compatible dictionaries.

OpenCV互換辞書向けの、単一HTMLで動作するArUcoマーカー生成ツールです。

## Features / 機能

### English

- Runs as a single `index.html` file.
- Runs locally in a browser.
- Generates ArUco markers as SVG and PNG.
- Requires no server, build step, external CSS, or external JavaScript.
- Includes OpenCV-compatible predefined ArUco dictionaries from 4x4 to 7x7, 1000 markers each.

### 日本語

- 単一の `index.html` ファイルとして動作します。
- ローカルブラウザで動作します。
- ArUcoマーカーをSVGおよびPNGとして生成します。
- サーバー、ビルド処理、外部CSS、外部JavaScriptは不要です。
- OpenCV互換のpredefined ArUco dictionaryとして、4x4から7x7まで各1000個のマーカーを含みます。

## Usage / 使い方

### English

Open `index.html` in a browser.

Select a dictionary and enter a marker ID.
The marker updates automatically, and you can download it as an SVG or PNG file.

You can also try the hosted web version:

```text
https://kemintas.com/arucogen/
```

Demo:

```text
https://kemintas-com.github.io/arucogen/
```

The hosted page is only a convenient public copy.
This tool does not depend on that URL and can run locally from `index.html`.

### 日本語

ブラウザで `index.html` を開きます。

辞書を選択し、マーカーIDを入力します。
マーカーは自動で更新され、SVGまたはPNGファイルとしてダウンロードできます。

公開中のWeb版でも試すことができます:

```text
https://kemintas.com/arucogen/
```

デモ:

```text
https://kemintas-com.github.io/arucogen/
```

この公開ページは利便性のための公開コピーです。
このツールはURLに依存せず、`index.html` をローカルで開いても動作します。

## Dictionaries / 辞書データ

### English

This project includes predefined ArUco dictionary data derived from OpenCV.
The initial version includes these OpenCV-compatible dictionaries:

### 日本語

このプロジェクトには、OpenCV由来のpredefined ArUco dictionary dataが含まれます。
初期版では、以下のOpenCV互換辞書を含みます:

```text
DICT_4X4_1000
DICT_5X5_1000
DICT_6X6_1000
DICT_7X7_1000
```

### English

The dictionary data is embedded in `index.html` so the tool can work without loading external files.

### 日本語

辞書データは `index.html` に埋め込まれているため、外部ファイルを読み込まずに動作します。

## License / ライセンス

### English

The original code in this repository is released under the MIT License.

The predefined ArUco dictionary data is derived from OpenCV and is provided under the Apache License 2.0 as third-party data.
OpenCV 4.5.0 and later are licensed under the Apache License 2.0.

See `NOTICE` for third-party attribution and `THIRD_PARTY_LICENSES/OpenCV-Apache-2.0.txt` for the Apache License 2.0 text.

### 日本語

このリポジトリの自作コードはMIT Licenseで公開します。

predefined ArUco dictionary dataはOpenCV由来の第三者データであり、Apache License 2.0に基づいて含めています。
OpenCV 4.5.0以降はApache License 2.0で提供されています。

第三者由来データの表記は `NOTICE`、Apache License 2.0本文は `THIRD_PARTY_LICENSES/OpenCV-Apache-2.0.txt` を確認してください。

## Notes / 注意

### English

- This project does not include OpenCV itself.
- This project does not include the original ArUco GPLv3 library.
- This project is not based on the source code of existing online ArUco marker generators.

### 日本語

- このプロジェクトはOpenCV本体を同梱しません。
- このプロジェクトには、元祖ArUco GPLv3ライブラリは含めません。
- このプロジェクトは、既存のオンラインArUcoマーカー生成ツールのソースコードを流用していません。
