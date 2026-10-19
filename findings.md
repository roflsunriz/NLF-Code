# 調査知見

- 実行用JavaScript/TypeScriptを持たない宣言型VS Code拡張である。通常のBunビルド対象として扱わない。
- `package.json`、`syntaxes/text.tmLanguage.json`、`language-configuration.json` の参照整合を確認し、最終的にはExtension Development Hostで言語モードとハイライトを検証する。
