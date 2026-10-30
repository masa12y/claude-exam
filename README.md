# Claude 認定試験 対策リポジトリ (claude-exam)

このリポジトリは、Anthropic 社の公式技術認定資格（Claude 認定試験）の合格に向けて、試験情報の収集、知識の整理、および演習問題の作成を行うための対策プロジェクトです。

現在は **Claude Certified Developer – Foundations（CCDV-F）** を対象としています。

---

## プロジェクトの目的

1. **公式試験ガイド・シラバスの整理**
   - 出題分野ごとの要点整理
   - 公式ドキュメントに基づく仕様、API設計、推奨実装の集約
2. **実務で使える開発知識の整理**
   - Messages API、ストリーミング、Prompt Caching、Message Batches API
   - Tool Use、Model Context Protocol（MCP）の実装
   - Agent SDK、エージェントワークフローの設計
   - Claude Code の活用とプロジェクト設定
   - 構造化出力、評価（LLM-as-a-Judge）、プロンプトインジェクション対策
3. **想定問題と演習の作成**
   - 選択式問題への対応力強化
   - 出題形式や設計上の判断基準の整理

---

## 対象試験

| 試験名 | 試験コード | 対象レベル | 主な対象者 |
|---|---|---|---|
| **Claude Certified Developer – Foundations** | **CCDV-F** | デベロッパー（開発者向け） | API連携、ツール利用、エージェント開発を行う技術者 |

---

## ディレクトリ構成

```text
claude-exam/
├── README.md                            # 本ファイル（プロジェクト目的・全体方針）
│
└── Developer–Foundations（CCDV-F）/     # デベロッパー試験対策
    ├── 試験ガイドmd                     # 公式試験ガイド（CCDV-F）
    ├── 01_MSO_Foundations/              # Module 1: MSO Foundations
    │   ├── README.md                    # 目次・リンク一覧
    │   ├── 01_モジュール概要.md
    │   ├── 02_LLMの振る舞い.md
    │   ├── 03_モデルと推論.md
    │   ├── 04_プロンプティングモード.md
    │   ├── 05_技術的な基盤.md
    │   ├── 06_まとめ.md
    │   └── 07_モジュール完了.md
    ├── 02_本番品質のプロンプティング、エージェント、ツールユース/ # Module 2
    │   ├── README.md                    # 目次・リンク一覧
    │   ├── 01_モジュール概要.md
    │   ├── 02_プロンプティングの技法.md
    │   ├── 03_拡張思考.md
    │   ├── 04_ツールユースとスキーマ設計.md
    │   ├── 05_ストリーミングレスポンス.md
    │   ├── 06_コンテキストエンジニアリング.md
    │   ├── 07_エージェント構築.md
    │   ├── 08_エージェントメモリー.md
    │   ├── 09_マルチモーダルとバッチによる取り込み.md
    │   ├── 10_モジュールのまとめ.md
    │   └── 11_モジュール完了.md
    └── ...
```

---

## CCDV-F（Developer – Foundations）試験概要

- **試験コード**: CCDV-F
- **問題数**: 53問（単一選択・複数選択）
- **試験時間**: 120分
- **合格ライン**: スケールスコア 720 / 1,000 点
- **受験料**: 125 USD
- **実施形式**: Pearson VUE（テストセンター、またはオンライン監督試験）
- **主な出題範囲**:
  - Claude API Mechanics（Messages API、トークン管理、ストリーミング等）
  - コストとパフォーマンスの最適化（Prompt Caching、Message Batches API）
  - エージェントとワークフロー設計（Agent SDK、オーケストレーター・ワーカー等）
  - Tool Use と Model Context Protocol（MCP）
  - Claude Code と開発ワークフロー（CLAUDE.md、CLI構成）
  - ソフトウェアエンジニアリングと安全性（構造化出力、評価手法、プロンプトインジェクション対策）
