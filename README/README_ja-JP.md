[中文](../README.md) | [English](README_en-US.md) | [繁體中文](README_zh-TW.md) | [Русский](README_ru-RU.md) | [日本語](README_ja-JP.md) | [한국어](README_ko-KR.md) | [Deutsch](README_de-DE.md) | [Français](README_fr-FR.md)

# Anytype フローティング目次

## プロジェクト背景
2022年から、Anytypeコミュニティのユーザーはフローティング目次機能の追加を要望してきました。残念ながら、2025年4月現在、この機能はまだ公式の開発ロードマップに含まれていません。興味深いことに、Anytypeの主要な競合製品であるNotionも、この機能の実装にあまり積極的ではありません。

## ソリューション
このプロジェクトは、カスタムCSSを使用してAnytypeにシンプルでエレガントなフローティング目次を実装しています。このソリューションは、コミュニティユーザー[@sandroid](https://community.anytype.io/t/custom-table-of-contents-custom-css/27360/8)のアプローチと一致しています。

設計プロセスでは、sspai.comのフローティング目次のスタイルを参考にしました。AnytypeがJSをサポートせずカスタムCSSのみをサポートしているという制限はありますが、最終的な結果は非常に優れたものとなっています。

## デモ
![フローティング目次デモ](../image/IMG_20250411_234639.gif)

## 機能
- シンプルでエレガントなフローティング目次のレイアウト
- ページスクロールに追従する目次で簡単なナビゲーション
- 目次項目のホバーエフェクト

## 使用方法
1. Anytypeを開き、`ファイル -> 開く -> カスタムCSS`に移動
2. `custom.css`または`custom.min.css`の内容を`カスタムCSS`ファイルにコピー
3. Anytypeを再起動して変更を適用

## 注意事項
- カスタムスタイリングが必要な場合は、`custom.css`のパラメータを変更できます 