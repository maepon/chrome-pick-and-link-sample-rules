# CONTRIBUTING.md
# Pick And Link サンプルルール集 コントリビューションガイドライン

このリポジトリでは、Chrome拡張機能「Pick And Link」用ルールファイル（YAML形式）およびサンプルファイル（Markdown形式）を管理しています。  
ルールやサンプルの追加にご協力いただける場合は、以下のガイドラインに従ってプルリクエスト（PR）を作成してください。

## プルリクエスト作成ルール

- 1つのプルリクエストでは、**原則として1つの新規ルールの追加**のみ行ってください。
- プルリクエスト本文に以下の情報を記載してください：
  - **概要**： 何を対象とするルールか
  - **対象カテゴリ**： books / security / commerce / sns / media など
  - **YAMLファイル名**： （例：`pick-code-link-doi.yaml`）
  - **動作確認済みか？**： Yes/No
  - **サンプルファイルの追加有無**： Yes/No
  - **その他注意事項**： （特殊な制約などあれば）

## ファイル配置ルール

- ルールファイル（YAML形式）は、必ずカテゴリごとのディレクトリ（`rules/<カテゴリ>/`）内に配置してください。
- ファイル名は以下の形式に統一してください：
  - ルールファイル名：`pick-code-link-[対象名].yaml`
  - サンプルファイル名（ある場合）：`pick-code-link-[対象名].md`
- 可能な限り、動作確認用のサンプルMarkdownファイルも `samples/` フォルダに追加してください。

## 命名規則

| 種別 | 命名ルール |
|:---|:---|
| YAMLファイル名 | `pick-code-link-[対象名].yaml` |
| サンプルファイル名 | `pick-code-link-[対象名].md` |
| ルールのtitle | 対象がわかりやすい短い表現（例：DOI to CrossRef） |

## マージポリシー

- プルリクエストは、**リポジトリオーナー（現在は管理者のみ）によってマージされます。**
- コントリビューター自身によるマージはできません。
- 動作確認を必ず行った上でプルリクエストを提出してください。

## 機密情報・社内利用ルールの取り扱いについて

- 社内利用や機密性が必要なルール・サンプルは、本公開リポジトリには追加しないでください。
- 公開が適切でない情報や、第三者に知られては困る内容は含めないようご注意ください。

## ライセンスについて

- 本リポジトリのライセンスは **MIT License** です。
- 投稿いただいたルールファイル・サンプルファイルもMITライセンスで提供されることに同意の上、プルリクエストを作成してください。

---

Thank you for contributing! 🚀
