# Pick And Link サンプルルール集

このリポジトリは、Chrome拡張機能「Pick And Link」用のルールファイル（YAML形式）をまとめたものです。

- [Pick&Link - Chrome ウェブストア](https://chromewebstore.google.com/detail/picklink/akbfaabjgmkdllgcgbkbkoefefgnoook)
- [maepon/chrome-pick-and-link](https://github.com/maepon/chrome-pick-and-link)

## 利用方法

1. このリポジトリからルールファイル（`.yaml`）をダウンロードしてください。
2. Pick And Linkのオプション画面で「インポート」機能を使い、ルールを取り込みます。
3. 必要なルールだけ選んでインポートできます。

## ルールカテゴリ一覧

### 📚 books
- [ISBNコードからAmazon/Yodobashi/Rakutenで検索](rules/books/pick-code-link-isbn.yaml)
- [ISSNコードから学術論文サイトで検索](rules/books/pick-code-link-issn.yaml)

### 🔒 security
- [CVE番号からNVD脆弱性情報を検索](rules/security/pick-code-link-cve.yaml)

### 🛒 commerce
- [JANコードからAmazonや楽天市場で商品検索](rules/commerce/pick-code-link-jan.yaml)

## サンプル動作確認用ファイル
- [ISBNテストサンプル](samples/pick-code-link-isbn.md)
- [ISSNテストサンプル](samples/pick-code-link-issn.md)
- [CVEテストサンプル](samples/pick-code-link-cve.md)
- [JANテストサンプル](samples/pick-code-link-jan.md)

## コントリビューションについて

ルールやサンプルの追加・改善などの貢献を歓迎しています。詳細なガイドラインは[CONTRIBUTING.md](CONTRIBUTING.md)をご参照ください。

## ライセンス
MIT License
