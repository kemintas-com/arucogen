# arucogen

Single-file ArUco marker generator for OpenCV-compatible dictionaries.

OpenCV互換辞書向けの、単一HTMLで動作するArUcoマーカー生成ツールです。

## Features / 機能

- Runs as a single `index.html` file
  - 単一の `index.html` ファイルとして動作します
- Runs locally in a browser
  - ローカルブラウザで動作します
- Generates ArUco markers as SVG and PNG
  - ArUcoマーカーをSVGおよびPNGとして生成します
- Requires no server, build step, external CSS, or external JavaScript
  - サーバー、ビルド処理、外部CSS、外部JavaScriptは不要です
- Includes OpenCV-compatible predefined ArUco dictionaries from 4x4 to 7x7, 1000 markers each
  - OpenCV互換のpredefined ArUco dictionaryとして、4x4から7x7まで各1000個のマーカーを含みます

## Usage / 使い方

Open `index.html` in a browser.

ブラウザで `index.html` を開きます。

Select a dictionary and enter a marker ID. The marker updates automatically.

辞書を選択し、マーカーIDを入力すると、マーカーは自動で更新されます。

You can download the generated marker as an SVG or PNG file.

生成したマーカーはSVGまたはPNGファイルとしてダウンロードできます。

You can also try the hosted web version:

https://kemintas.com/arucogen/

The hosted page is only a convenient public copy. This tool does not depend on that URL and can run locally from `index.html`.

公開中のWeb版でも試すことができます:

https://kemintas.com/arucogen/

この公開ページは利便性のための公開コピーです。このツールはURLに依存せず、`index.html` をローカルで開いても動作します。

## Dictionaries / 辞書データ

This project includes predefined ArUco dictionary data derived from OpenCV.

このプロジェクトには、OpenCV由来のpredefined ArUco dictionary dataが含まれます。

The initial version includes these OpenCV-compatible dictionaries:

初期版では、以下のOpenCV互換辞書を含みます:

```text
DICT_4X4_1000
DICT_5X5_1000
DICT_6X6_1000
DICT_7X7_1000
```

The dictionary data is embedded in `index.html` so the tool can work without loading external files.

辞書データは `index.html` に埋め込まれているため、外部ファイルを読み込まずに動作します。

## License / ライセンス

The original code in this repository is released under the MIT License.

このリポジトリの自作コードはMIT Licenseで公開します。

The predefined ArUco dictionary data is derived from OpenCV and is provided under the Apache License 2.0 as third-party data. OpenCV 4.5.0 and later are licensed under the Apache License 2.0.

predefined ArUco dictionary dataはOpenCV由来の第三者データであり、Apache License 2.0に基づいて含めています。OpenCV 4.5.0以降はApache License 2.0で提供されています。

See `NOTICE` for third-party attribution and `THIRD_PARTY_LICENSES/OpenCV-Apache-2.0.txt` for the Apache License 2.0 text.

第三者由来データの表記は `NOTICE`、Apache License 2.0本文は `THIRD_PARTY_LICENSES/OpenCV-Apache-2.0.txt` を確認してください。

## Notes / 注意

This project does not include OpenCV itself.

このプロジェクトはOpenCV本体を同梱しません。

This project does not include the original ArUco GPLv3 library.

このプロジェクトには、元祖ArUco GPLv3ライブラリは含めません。

This project is not based on the source code of existing online ArUco marker generators.

このプロジェクトは、既存のオンラインArUcoマーカー生成ツールのソースコードを流用していません。
