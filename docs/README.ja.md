# Awesome Moli [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <a href="../README.md">English</a> | <a href="README.zh-CN.md">简体中文</a> | <strong>日本語</strong> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.es.md">Español</a> | <a href="README.ko.md">한국어</a>
</p>

> [Moli](https://github.com/lexmount/moli) は AI エージェント向けのオープンソースのヘッドレスブラウザーです。Moli を活用・拡張・配布するプロジェクトを、ブラウザーの自動化ツールからフレームワークとの連携、派生プロジェクト、デプロイ方法、開発事例まで紹介します。

## 目次

- [フォークと派生プロジェクト](#forks-and-derivatives)
- [テスト・QA ツール](#testing-and-qa-tools)
- [ブラウザー自動化とワークフロー](#browser-automation-and-workflows)
- [Web レンダリングとデータ抽出](#web-rendering-and-extraction)
- [エージェントフレームワークとワークスペース](#agent-frameworks-and-workspaces)
- [パッケージングとデプロイ](#packaging-and-deployment)
- [開発事例と評価](#development-examples-and-evaluations)

<a id="forks-and-derivatives"></a>

## フォークと派生プロジェクト

- [Limo](https://github.com/Spxg/limo) - Moli が提供するブラウザー Web API 一式を使い、ターミナルの JavaScript から DOM 要素を作成したりクリックイベントを処理したりできます。
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - HTTP と WebSocket に共通の Rust 通信層を使い、Chrome をモデルにしたネットワークプロファイルを備える Moli のフォーク。
- [pilot](https://github.com/WSAdam/pilot) - Playwright や Playwright MCP から直接起動でき、必要に応じてウィンドウでエージェントの操作を見守れる Moli 派生ブラウザー。

<a id="testing-and-qa"></a>
<a id="testing-and-qa-tools"></a>

## テスト・QA ツール

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - ローカルプロセス管理と既存 CDP エンドポイントへの接続に対応する、実験的な Moli ヘルパーを備えた E2E テストフレームワーク。
- [e2e](https://github.com/e2e-inc/e2e) - 上流にマージされた Moli アダプターが、並列 Web テストのワーカーごとに専用のローカルブラウザーを管理します。
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - 固定の公開ページを Moli で抽出検査し、Chrome による視覚的 QA にフォールバックできる MCP 開発ツール。

<a id="browser-tools-and-mcp"></a>
<a id="browser-automation-and-workflows"></a>

## ブラウザー自動化とワークフロー

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Playwright/CDP 経由で利用できる、任意の Moli バックエンドを備えたブラウザー自動化ブリッジ。
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - ヘッドレス操作には Moli、対話式ログインには Chrome を使い分けてチャットの Web セッションを管理する Go 製 CLI。
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - Linux x86_64 で管理対象の Moli エンジンとサンドボックス化されたワーカーを提供する MCP ブラウザーサーバー。
- [dsh-moli](https://github.com/27painter/dsh-moli) - ページ抽出、JavaScript 評価、スクリーンショット、PDF、エンジン診断に対応する DeepSeek Harness のコミュニティプラグイン。
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - Moli で応募フォームに入力し、送信前にユーザーの確認を求める実験的な求職スキル。

<a id="web-extraction-and-research"></a>
<a id="web-rendering-and-extraction"></a>

## Web レンダリングとデータ抽出

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - ローカル Moli CDP バックエンドと、個別の Chrome フォールバック方針を備えたページから Markdown への変換サービス。
- [A3S Search](https://github.com/A3S-Lab/Search) - Moli CLI レンダラーと描画の同時実行数制限を備えた、組み込み可能な検索エンジン。
- [Brains](https://github.com/YuniqueUnic/brains) - URL インポート時に Moli 描画を選択できる、バージョン管理付き Markdown ナレッジストア。
- [CTI Expert](https://github.com/7onez/cti-expert) - JavaScript 実行後の DOM 抽出に Moli を使い、視覚的証拠の取得には Chromium を併用する脅威インテリジェンスツール。
- [HEIS](https://github.com/u4399com-beep/heis) - Moli の取得とスクリプト評価を Go の HTTP ブリッジで公開する小説収集システム。
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - ページ読み取りのフォールバックチェーンに Moli 描画を組み込んだ Hermes 調査ツール。
- [Lens](https://github.com/bysages/lens) - CDP 経由の Moli でスクリーンショットとページ読み取りを行う TypeScript Web ツール集。
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - ブラウザーアクセサーが Moli CLI で動的ページを描画する Rust データ収集システム。
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - 指定した URL を読み取り、出典の保存やページのスナップショットの比較ができるベータ版のローカル MCP 調査ツール。
- [molisnap](https://github.com/7a6163/molisnap) - キャッシュとサイトマップの事前読み込みに対応する、検索クローラーおよび AI ボット向けの SPA プリレンダリングサービス。
- [PageSift](https://github.com/YOLOW92/pagesift) - Lightpanda → Moli → Chrome のブラウザー選択チェーンを持つ Rust の Web・文書抽出サービス。
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - HTTP 抽出で内容が足りない場合に Moli で JavaScript ページを描画し、Chromium にもフォールバックする Windows 向けエージェントツール配布物。
- [stvdy](https://github.com/jettapindika/stvdy) - Exa、Moli、HTTP/readability のフォールバックチェーンで Web 資料を取り込む学習ワークスペース。
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - 外向き通信の分離を別途設定すると Moli によるページ抽出を任意で有効にできる家庭向け AI ワークスペース。

<a id="agents-and-workspaces"></a>
<a id="agent-frameworks-and-workspaces"></a>

## エージェントフレームワークとワークスペース

- [A3S Code](https://github.com/A3S-Lab/Code) - ヘッドレス Web 検索バックエンド用に、検証済みの Moli ランタイムを準備するエージェントフレームワーク。
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - Moli による Web 読み取りと、Playwright MCP を介したエージェントごとのスクリプト操作を提供するコーディングエージェント管理基盤。
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - Moli を優先してページを描画し、セルフホストの Firecrawl、通常の HTTP へとフォールバックするエージェント用ワークフローツール。
- [AION](https://github.com/JayCRL/AION) - web.read ツールで Moli を呼び出し、描画後の Markdown または構造化 DOM データを返すエージェント基盤。
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - qq_webfetch ツールでローカル Moli による任意のページ描画を利用できる QQ ボット連携。
- [Internkim](https://github.com/yeomyeonggeori/internkim) - 公開ページの閲覧用に Moli ブラウザーランタイムを備えた、チーム向けエージェントワークスペース。
- [Lumen](https://github.com/Andrea17982/Lumen) - Moli を同梱し、複数のモデルおよび CLI アダプターでブラウザーツールを共有するデスクトップのエージェントワークスペース。
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - コンテナー化された Moli ブラウザーと、認証付き HTTP/WebSocket CDP ゲートウェイを備えたコーディングエージェント実行基盤。
- [Qianxun](https://github.com/imxood/qianxun) - ローカル Moli 実行ファイルの検出とバージョン確認に対応する、DeepSeek Harness 向けの Tauri デスクトップ作業環境。
- [Relay](https://github.com/arcwright42/Relay) - 時間と出力量を制限した Moli のページ取得、およびブラウザーのインストール管理を提供するエージェントランタイム。
- [Wick](https://github.com/yogasw/wick) - 任意の Moli ブラウザーコネクター、CDP セッション、Markdown 抽出を備えた Go 製エージェントホスト。

<a id="deployment-and-packaging"></a>
<a id="packaging-and-deployment"></a>

## パッケージングとデプロイ

コミュニティによるインストール定義とデプロイテンプレート。

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - コミュニティが管理する、Moli 向け 1Panel アプリケーション定義と Docker イメージビルド。
- [A3S CLI](https://github.com/A3S-Lab/CLI) - 対象プラットフォームごとの Moli ランタイムを同梱する A3S コマンドライン配布物。
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Moli バイナリーと同じリリースの公式エージェントスキルをインストールする、コミュニティの Homebrew tap。
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - リモート CDP、ホストされた DevTools、Caddy/Authentik の入口を備えた NixOS Moli サービス。
- [moli-snap](https://github.com/sidalit/moli-snap) - Linux で Moli CLI と自動化サーバーを実行するための非公式 Snap パッケージ。
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - バージョンを固定した Moli リリースバイナリーと、その実行時依存関係を扱う NixOS パッケージ定義。
- [Railway Moli](https://github.com/two-workspaces/moli) - トークン認証付き Caddy ゲートウェイと公開 WebSocket アドレスの書き換えを備えた Railway デプロイテンプレート。

<a id="experimental-and-development-examples"></a>
<a id="development-examples-and-evaluations"></a>

## 開発事例と評価

プロトタイプ、開発スクリプト、評価レポート。テスト結果は各プロジェクトの作者による報告です。

- [Aveli](https://github.com/pkmdev-sec/aveli) - ブラウザーエージェント向けの実験的な Moli ランタイムと互換性プローブ。
- [govio-map](https://github.com/chenxinma/govio-map) - アプリケーションの設定ダイアログで入力フォーカスと検証処理を確認する CDP スモークテストスクリプト。
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - Moli CDP でレスポンシブレイアウトとダウンロードの流れを確認する開発用スクリプト。
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Moli のバージョン別評価、回帰、再テスト、Chromium との比較を記録するクローラープロジェクト。
- [llama.rs](https://github.com/yablokolabs/llama.rs) - Moli で Rust/WASM チャットアプリケーションの JavaScript インターフェースを動かすブラウザーテストスクリプト。
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Moli による E2E スクリプトと、明示的なローカル Chromium フォールバックを備えた地図アプリケーション。
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Moli CDP の観察・操作と Apofasi の意思決定を組み合わせた Rust ブラウザーエージェントのプロトタイプ。
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - 購入者の承認操作に Moli CDP を使用する、PayPal サンドボックス決済のサンプル。
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - 標準ビルドとは別に、Linux 上で root 権限なしに Moli の受け入れテストを起動するランチャー。

## 貢献

Moli のフォークや派生プロジェクト、新しい活用例を歓迎します。プロジェクトの追加や既存の説明の修正は[貢献ガイド](../CONTRIBUTING.md)をご覧ください。

## 注記

**2026-11-19** に公開コードとドキュメントを確認しました。本番での利用状況、顧客関係、テスト結果の独立した検証は対象外です。確認したコミットへのリンク、証拠のスナップショット、過去の言及や参照できなかったリポジトリは[確認記録](REVIEW.md)にまとめています。
