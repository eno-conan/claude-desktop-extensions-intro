# Claude Desktop Extensions 
少し触ってみました。

https://www.anthropic.com/engineering/desktop-extensions

## 公式リポジトリ

https://github.com/anthropics/dxt/tree/main

## 記事
Qiitaで公開しています。

https://qiita.com/eno49conan/items/a7ea077d6bc643e5ee23

## 作成時の参照情報
- [examples/file-manager-python(フォルダ)](https://github.com/anthropics/dxt/tree/main/examples/file-manager-python)
    - MCPツールとして用いるプログラムと設定ファイル
- [CLI.md](https://github.com/anthropics/dxt/blob/main/CLI.md)
    - 作成時に必要なものを含めたコマンド情報を記載
- [MANIFEST.md](https://github.com/anthropics/dxt/blob/main/MANIFEST.md)
    - `manifest.json`の各フィールドに対する説明

## コマンド
### プロジェクト作成
```
npx @anthropic-ai/dxt init
```
### バリデーションチェック
```
npx @anthropic-ai/dxt validate
```
### パッケージ化
```
npx @anthropic-ai/dxt pack
```