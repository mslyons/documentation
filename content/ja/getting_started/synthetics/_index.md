---
title: Synthetic モニタリングの概要
kind: documentation
further_reading:
  - link: /synthetics/browser_tests
    tag: ドキュメント
    text: ブラウザテストについて
  - link: /synthetics/api_tests
    tag: ドキュメント
    text: API テストについてより詳しく学ぶ
  - link: '/synthetics/browser_tests/#subtests'
    tag: ドキュメント
    text: ブラウザサブセットを作成
  - link: /synthetics/settings/
    tag: ドキュメント
    text: 高度な Synthetic モニタリング設定を構成する
---
## 概要

Datadog Synthetic モニタリングは API エンドポイントのアップタイムを監視する API テスト、そして主要なユーザージャーニーをチェックするブラウザテストの 2 つを使用してお使いのアプリケーションを監視します。テストは管理ロケーションとプライベートロケーションのどちらからでも実行可能です。Synthetic モニタリングはアプリケーション上でのアップタイムの確保、地域的な問題の特定、主要なウェブトランザクションの稼働状況の確認にとても有用です。

{{< img src="synthetics/synthetics_home.png" alt="Synthetic モニタリングのホームページ" >}}

Synthetic モニタリングをメトリクス、トレース、ログと紐付けることで、ユーザーが利用しているシステム全体のパフォーマンス状況を Datadog 上で把握できます。 ステータス更新、応答時間、アップタイムなど、すべての情報の詳細が [Synthetic モニタリング][1] のホームページにリアルタイムで表示されます。

以下のガイドで、Datadog で Synthetic テストをセットアップする手順をご覧いただけます。各セクションでブラウザまたは API テストの設定方法、プライベートロケーションでテストを構成して内部のアプリケーションやプライベート URL を監視する方法をご紹介しています。

## 前提条件

[Datadog アカウント][2]をまだ作成していない場合は作成します。

## 初めてテストを構成する場合

- [プライベートロケーションを作成][3] (必要な場合)
- [ブラウザテストを作成][4]
- [API テストを作成][5]

## 次のステップ

{{< whatsnext desc="Synthetic テストを作成した後は、以下のページを参照してください。">}}
{{< nextlink href="/synthetics/browser_tests" tag="ドキュメント" >}}ブラウザテストの詳細はこちら{{< /nextlink >}}
{{< nextlink href="/synthetics/api_tests" tag="ドキュメント" >}}API テストの詳細はこちら{{< /nextlink >}}
{{< nextlink href="/synthetics/browser_tests/#subtests" tag="ドキュメント" >}}ブラウザのサブテストを作成する{{< /nextlink >}}
{{< nextlink href="/synthetics/settings/" tag="ドキュメント" >}}高度な Synthetic 設定を構成する{{< /nextlink >}}
{{< /whatsnext >}}

[1]: https://app.datadoghq.com/synthetics/list
[2]: https://www.datadoghq.com/
[3]: /ja/getting_started/synthetics/private_location/
[4]: /ja/getting_started/synthetics/browser_test/
[5]: /ja/getting_started/synthetics/api_test/