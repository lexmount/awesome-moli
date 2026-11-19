<h1 align="center">Awesome Moli</h1>

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

- **[Limo](https://github.com/Spxg/limo) - Moli が備えるすべてのブラウザー Web API を使って、ターミナルで JavaScript を実行できます。**
- [moli-stealth](https://github.com/Stravia-AI/moli-stealth) - Moli の HTTP 接続と WebSocket 接続に Chrome に近いネットワーク設定を適用します。
- [pilot](https://github.com/WSAdam/pilot) - Playwright MCP でエージェントがページを操作する様子をウィンドウで見られます。

<a id="testing-and-qa"></a>
<a id="testing-and-qa-tools"></a>

## テスト・QA ツール

- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - 実験的な Moli バックエンドで E2E テストを実行できます。
- **[e2e](https://github.com/e2e-inc/e2e) - 自然言語の指示で購入手続きなどを Moli 上でテストでき、検証済みの操作はモデルを再度呼び出さずに再生できます。**
- [KMJ CodeBridge](https://github.com/kmjtechno/kmj-codebridge) - 指定の公開テストページから本文を抽出できるか、必要に応じて Moli で確認します。

<a id="browser-tools-and-mcp"></a>
<a id="browser-automation-and-workflows"></a>

## ブラウザー自動化とワークフロー

- [Browser Bridge for Muse](https://github.com/rehantheorylab-pixel/browser-bridge-for-muse) - Muse の Playwright ブラウザーとしてローカルの Moli を選べます。
- [chatctl](https://github.com/ironpark/toolz/tree/main/cli/chatctl) - Chrome でログインすれば、Moli を使ってターミナルからチャット履歴を読めます。
- [Delta Browser](https://github.com/DevAnimecx/deltabrowser) - x86_64 Linux 上で Moli をサンドボックスに隔離して MCP のブラウザーセッションを実行します。
- **[dsh-moli](https://github.com/27painter/dsh-moli) - 動的なページを Markdown に変換する DeepSeek Harness 向けのコミュニティ製プラグインです。**
- [Moli Job Apply](https://github.com/mcaupybugs/claude-job-apply-skill-moli) - 応募フォームに入力し、送信前に確認を求める実験的な求職アシスタントです。

<a id="web-extraction-and-research"></a>
<a id="web-rendering-and-extraction"></a>

## Web レンダリングとデータ抽出

- [888-url2md](https://github.com/tbdavid2019/888-url2md) - 複数の URL をまとめて Markdown に変換し、JavaScript が必要なページは Moli で描画します。
- [A3S Search](https://github.com/A3S-Lab/Search) - 検索で見つけた JavaScript 依存のページを Moli で読み取ります。
- [Brains](https://github.com/YuniqueUnic/brains) - Moli を使って動的なページを履歴付きの Markdown ノートとして保存できます。
- **[CTI Expert](https://github.com/7onez/cti-expert) - 脅威情報の調査で、JavaScript の実行後に表示されるページ内容を Moli で取得します。**
- [HEIS](https://github.com/u4399com-beep/heis) - Moli を使って動的に読み込まれるウェブ小説の章を収集できます。
- [hermes-dev](https://github.com/Sucotasch/hermes-dev) - Hermes Deep Research の通常の取得方法で本文を読めないときに Moli で描画します。
- [Lens](https://github.com/bysages/lens) - HTTP API 経由で Moli を使ってウェブページのスクリーンショットを撮れます。
- [ModalPrism](https://github.com/MistLoom/ModalPrism) - Moli で描画した動的ページを保存し、収集時の内容を後から確認できます。
- [Moli Web Research](https://github.com/assistifyai405/moli-webonderzoek) - 保存したウェブページのスナップショットを比較できる、ベータ版のローカル MCP ツールです。
- [molisnap](https://github.com/7a6163/molisnap) - シングルページアプリを事前に描画して、検索クローラーや AI ボットが読める HTML にします。
- [PageSift](https://github.com/YOLOW92/pagesift) - Lightpanda で読み取れない iframe の内容を Moli で取得します。
- [Smart Tool](https://github.com/AllanSantos-DV/smart-tool-dist) - Windows のコーディングエージェントが HTTP だけで本文を取得できないときに Moli を使えます。
- [stvdy](https://github.com/jettapindika/stvdy) - Exa で本文を取得できないときは、Moli でウェブページを学習資料として取り込みます。
- [Vanilla](https://github.com/easylearnfromtw/vanilla) - 外向きの通信を隔離した環境で、Moli を有効にして公開ウェブページの本文を取り込めます。

<a id="agents-and-workspaces"></a>
<a id="agent-frameworks-and-workspaces"></a>

## エージェントフレームワークとワークスペース

- [A3S Code](https://github.com/A3S-Lab/Code) - コーディングエージェントのウェブ検索用に、検証済みの Moli を自動で用意します。
- [agent-fabric](https://github.com/BlueTeam-OU/agent-fabric) - コーディングエージェントごとに専用の一時的な Moli ブラウザーセッションを用意します。
- [agnostic-router-kit](https://github.com/adelvillar1/agnostic-router-kit) - ワークフローで JavaScript ページを読み取るときは、まずローカルの Moli を使います。
- [AION](https://github.com/JayCRL/AION) - Moli で読み取った動的ページをエージェントの作業画面にカード形式で表示します。
- [dsh-qq-bot](https://github.com/arrow1031-dev/dsh-qq-bot) - QQ ボットが必要に応じてローカルの Moli でリンク先を Markdown として読み取れます。
- [Internkim](https://github.com/yeomyeonggeori/internkim) - チームの AI アシスタントがローカルの Moli を使って公開ウェブページを閲覧できます。
- [Lumen](https://github.com/Andrea17982/Lumen) - Claude Code や Codex がデスクトップで共用できる Moli ブラウザーツールを同梱します。
- [mem0-omp](https://github.com/millianlmx/mem0-omp) - コーディングエージェントがトークン認証を通してコンテナ内の Moli ブラウザーに接続できます。
- [Qianxun](https://github.com/imxood/qianxun) - DeepSeek Harness のデスクトップアプリで、ローカルにある Moli とそのバージョンを検出します。
- [Relay](https://github.com/arcwright42/Relay) - Moli でリンク先を読み込み、ページがタイムアウトしてもプロンプトを送信できます。
- [Wick](https://github.com/yogasw/wick) - Go エージェントが必要に応じてローカルの Moli でウェブページを Markdown として読めます。

<a id="deployment-and-packaging"></a>
<a id="packaging-and-deployment"></a>

## パッケージングとデプロイ

コミュニティによるインストール定義とデプロイテンプレート。

- [1Panel App](https://github.com/skingko/1panel_app/tree/localApps/apps/x-moli) - コミュニティ製のパッケージで、1Panel から Moli をデプロイできます。
- [A3S CLI](https://github.com/A3S-Lab/CLI) - A3S のコマンドラインツールに、対象プラットフォーム用の Moli ランタイムを同梱します。
- [Homebrew Moli](https://github.com/hoishing/homebrew-moli) - Moli と対応する公式エージェントスキルをまとめて導入できるコミュニティ製の Homebrew tap です。
- [Lattice](https://github.com/mytecor/lattice/tree/main/profiles/moli) - NixOS 上で Moli をホストし、DevTools からリモートでページをデバッグできます。
- [moli-snap](https://github.com/sidalit/moli-snap) - スクリーンショットや PDF 用のフォントを Moli に同梱した非公式の Linux 向け Snap です。
- [orbsh/nixos](https://github.com/orbsh/nixos/blob/main/modules/system/units/moli.nix) - Moli のバージョンとチェックサムを固定し、NixOS で同じバイナリをインストールできます。
- [Railway Moli](https://github.com/two-workspaces/moli) - Railway に Moli をデプロイし、トークン認証付きでブラウザーにリモート接続できます。

<a id="experimental-and-development-examples"></a>
<a id="development-examples-and-evaluations"></a>

## 開発事例と評価

プロトタイプ、開発スクリプト、評価レポート。テスト結果は各プロジェクトの作者による報告です。

- [Aveli](https://github.com/pkmdev-sec/aveli) - ブラウザーエージェントがローカルの Moli に接続できるかを試す実験的なチェックです。
- [govio-map](https://github.com/chenxinma/govio-map) - Moli で設定欄に一文字ずつ入力し、フォーカスが外れないか確かめます。
- [Hydra Downloader](https://github.com/juanpimg/hydradownloader) - スマートフォンの画面幅を変え、ダウンロード画面がはみ出さないか Moli で確認します。
- [laravel-domains](https://github.com/yepbro/laravel-domains) - Moli の複数のバージョンと Chromium でウェブクローラーの動作を比較します。
- [llama.rs](https://github.com/yablokolabs/llama.rs) - ローカルの WebAssembly チャットデモが質問に答えられるか Moli で確認します。
- [Master Maps](https://github.com/0bifthenelse/master-maps) - Moli で 3D 地図の E2E テストを実行し、必要ならローカルの Chromium に切り替えます。
- [Molifasi](https://github.com/A3S-Lab/Molifasi) - Apofasi が次の操作を決め、Moli がページ上で実行するエージェントの試作版です。
- [ScopePay AI](https://github.com/yablokolabs/scopepay-ai) - PayPal のサンドボックスで、購入者が支払いを承認する流れを Moli でテストします。
- [SmartSpecPro](https://github.com/naibarn/SmartSpecPro) - Linux で root 権限を使わない受け入れテストに限って Moli を起動します。

## 貢献

Moli のフォークや派生プロジェクト、新しい活用例を歓迎します。プロジェクトの追加や既存の説明の修正は[貢献ガイド](../CONTRIBUTING.md)をご覧ください。

## 注記

**2026-11-19** に公開コードとドキュメントを確認しました。本番での利用状況、顧客関係、テスト結果の独立した検証は対象外です。確認したコミットへのリンク、証拠のスナップショット、過去の言及や参照できなかったリポジトリは[確認記録](REVIEW.md)にまとめています。
