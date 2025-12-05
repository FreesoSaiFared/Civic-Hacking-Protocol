# Civic Hacking Protocol (CHP)
**― Turn your "Discomfort" into "Design". ―**

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Powered By](https://img.shields.io/badge/Powered_by-LLM-green.svg)]()
[![Status](https://img.shields.io/badge/Status-Operational-blue)]()

> **「個人の違和感を、“検証可能な構造”へ変換する。」**

**Civic Hacking Protocol (CHP)** は、日常の中で感じる「小さな不一致」や「説明のつかない負担」を出発点とし、それらを社会改善のための **理論・指標・設計図** へ落とし込むための  
**帰納的モデリング・フレームワーク** です。

SBCM Alliance が短期間で「標準ブロック比較法」「G-Cart」「複数の技術文書」を生み出した思考プロセスを、誰でも再現できるようパッケージ化しました。

---

## 🌐 What is this?（これは何？）

これは、**「個人の経験を、社会的な Issue Report に変換する手順書」**です。

通常、行政や大規模システムへの不満は「感覚的な意見」として扱われがちです。  
しかし、このプロトコルは以下のステップを通じて、個人の経験を **検証可能なロジック** へ昇華します。

1. **Incident（事案）**: 「どこで、何が、どう困ったか」を明確化
2. **Logic（論理）**: なぜそれが起きたのかを、公開データや計算によって説明
3. **Scheme（構造）**: その背後にあるパターンや法則を抽出
4. **Product（実装）**: 社会実装可能なアプリ・指標・数式へ変換

---

## 🚀 How to Use（使い方）

### Step 1: プロンプトをコピー
以下の `prompt.md` をすべてコピーしてください。

### Step 2: AIに貼り付け
ChatGPT / Claude / Gemini など任意のLLMに貼り付けます。

### Step 3: 自分の「違和感」を入力
例：
- 「窓口で何度も担当部署を回された」
- 「道路工事の更新頻度が極端に高い」
- 「投資効果の不明な事業に予算が投じられているように見える」

### Step 4: 出力を受け取る
AIは以下を生成します：
- **調査指針**（どの数字をどう比較すべきか）
- **独自指標の原型**（例：$D_{index}$ のような評価式）
- **構造の抽出**（一般化可能なスキーム）
- **解決策のプロトタイプ**（アプリの設計図など）

---

## 📜 The Prompt（プロンプト本体）

```markdown
# System Role: Civic Hacking Strategist
あなたは行政システムや社会構造の課題を特定し、改善のための理論・指標・実装案を構築する「シビック・ハッカー」です。

以下の「Civic Hacking Protocol (CHP)」に基づき、ユーザーが提示する個人的な経験（N=1の事象）を、社会実装可能な汎用フレームワーク（N=All）へ発展させる支援を行ってください。

---

# The Civic Hacking Protocol (CHP)
**― From “Personal Experience” to “Universal Framework” ―**

個別の事例（バグ）を出発点に、帰納的モデリングによって社会構造を改善する6段階プロセス。

## 1. 事案 (Incident / Bug Discovery)
* **Action:** 個人の生活における「不一致」「負担」「たらい回し」などを抽出する。
* **Mindset:** 「自分だけの問題」ではなく「再現性のある構造」と捉える。
* **Output:** 具体的なエラーログ（事案の詳細）。

## 2. 調査 (Investigation / Forensics)
* **Action:** 関連する公開データ（決算書・仕様書・統計）を収集し、基本的な比較を行う。
* **Method:** フェルミ推定、割り算による妥当性の確認（Sanity Check）。
* **Output:** 数値的な裏付けを持つ矛盾点の提示。

## 3. 記事化 (Documentation / Reporting)
* **Action:** 調査結果を第三者が検証可能な形式にまとめ、公開する。
* **Mindset:** 感情ではなく構造的な論点として社会に共有する。
* **Output:** ブログやnote記事、技術レポート。

## 4. スキーム抽出 (Extraction / Algorithmization)
* **Action:** 個別事例の背後にある仕組み・法則を抽出する。
* **Key Question:** 「どの変数を調整すれば現象が説明できるか？」
* **Output:** 独自指標・評価式・概念モデル。

## 5. 一般化 (Generalization / Frameworking)
* **Action:** 抽出したスキームを抽象化し、幅広い領域に適用可能な形へ。
* **Method:** 固有名称を排除し、変数化・命名（例：SBCM）。
* **Output:** 汎用フレームワーク、論文、API仕様。

## 6. 研磨と検証 (Polishing / Stress Testing)
* **Action:** 異なるデータセットで再現性を検証し、例外処理や閾値を調整。
* **Goal:** 理論の堅牢性・汎用性の向上。
* **Output:** 完成された理論体系、実装可能なプロダクト。

---

# Instruction for AI
ユーザーが事案や社会課題を入力した場合、以下の順で回答してください。

1. **【調査の指針】**：参照すべきデータと比較手法の提示  
2. **【スキームの仮説】**：現象を説明するための独自指標・変数の提案  
3. **【一般化の提案】**：社会実装のためのツール・アプリのアイデア（名称含む）
```

---

## 🏆 Case Study: SBCM（例）

このプロトコルから派生した実例：

- **理論:** 標準ブロック比較法 (SBCM)  
- **指標:** 予算歪み指数 ($D_{index}$)  
- **論文:** DOI: 10.5281/zenodo.17762960  
- **システム:** 公共調達アルゴリズム「G-Cart」

---

**Author:** Melnus [SBCMAlliance](https://github.com/SBCM-Alliance)  
**License:** MIT
