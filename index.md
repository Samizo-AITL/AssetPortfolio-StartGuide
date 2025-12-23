---
layout: default
title: AssetPortfolio Start Guide
# math: katex   # 数式必要なら
---

---

# 💰 **AssetPortfolio Start Guide**  

[![Samizo-AITLポータルサイトに戻る](https://img.shields.io/badge/Samizo--AITL%20ポータルサイトに戻る-brightgreen)](https://samizo-aitl.github.io/) [![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**テクノロジー時代のための資産運用・投資学習教材**  
*Asset Management & Investment Learning Guide for the Technology Era*

---

## 🔗 公式リンク | Official Links

| 言語 / Language | GitHub Pages 🌐 | GitHub 💻 |
|-----------------|----------------|-----------|
| 🇯🇵 Japanese | [![GitHub Pages JP](https://img.shields.io/badge/GitHub%20Pages-日本語版-brightgreen?logo=github)](https://samizo-aitl.github.io/AssetPortfolio-StartGuide/) | [![GitHub Repo JP](https://img.shields.io/badge/GitHub-日本語版-blue?logo=github)](https://github.com/Samizo-AITL/AssetPortfolio-StartGuide) |
| 🇺🇸 English | [![GitHub Pages EN](https://img.shields.io/badge/GitHub%20Pages-English-brightgreen?logo=github)](https://samizo-aitl.github.io/AssetPortfolio-StartGuide/en/) | [![GitHub Repo EN](https://img.shields.io/badge/GitHub-English-blue?logo=github)](https://github.com/Samizo-AITL/AssetPortfolio-StartGuide/tree/main/en) |

---

## 📘 **概要｜Overview**

このリポジトリは、**テクノロジー分野に注目した個人資産運用**を学ぶための**2部構成教材**です。  
**インフレや年金リスクに備えながら、ChatGPTやETFを活用**し、**自分でポートフォリオを構築・評価できる力**を育てます。

This repository is a two-part learning guide designed to help individuals understand and practice **technology-focused asset management and investment**, using **ChatGPT**, **ETFs**, and **data-backed decision-making**.

---

## 📚 **教材構成｜Structure**

```plaintext
AssetPortfolio-StartGuide/
├── chapters/                # 教材本文（全14章×2部構成）
│   ├── part1_foundation/       ← 投資の基礎編（全7章）
│   └── part2_techstocks/       ← テクノロジー銘柄実践編（全7章）
├── templates/              # ChatGPTテンプレート集（実践支援用）
├── assets/                 # 図表・補助資料（必要に応じて）
└── README.md
```

---

## 🧠 **2部構成の内容｜Two-Part Curriculum**

### 🔹 **第1部：[投資の基本と実践準備](./chapters/part1_basics/)**（*Basic Investing Guide*）

- [第1章：なぜ今、資産運用が必要か](./chapters/part1_basics/01_why_invest.md)
- [第2章：投資と資産運用の基本用語](./chapters/part1_basics/02_terms.md)
- [第3章：NISAとは何か？制度と使い方](./chapters/part1_basics/03_nisa_intro.md)
- [第4章：どこで始める？証券口座の選び方](./chapters/part1_basics/04_choose_broker.md)
- [第5章：実際の始め方（スマホ／iPad／PC対応）](./chapters/part1_basics/05_how_to_start.md)
- [第6章：初心者向けのおすすめ商品と配分](./chapters/part1_basics/06_products_allocation.md)
- [第7章：リバランスと中長期戦略](./chapters/part1_basics/07_rebalance_strategy.md)
- 📌 **特別編**：[ChatGPTを使った資産設計](./chapters/part1_basics/sp_chatgpt_design.md)

---

### 🔹 **第2部：[テクノロジー銘柄実践ガイド](./chapters/part2_techstocks/)**（*Tech Stocks Strategy*）

- [第8章：テクノロジー投資って何？](./chapters/part2_techstocks/08_intro_tech.md)
- [第9章：有望分野の選び方](./chapters/part2_techstocks/09_focus_sectors.md)
- [第10章：ETFで銘柄を逆引きする](./chapters/part2_techstocks/10_etf_reverse_lookup.md)
- [第11章：企業を深掘りする（事業分析・IR）](./chapters/part2_techstocks/11_deep_dive.md)
- [第12章：ChatGPTで比較分析する](./chapters/part2_techstocks/12_compare_stocks.md)
- [第13章：自分だけの銘柄リストを作る](./chapters/part2_techstocks/13_make_your_list.md)
- [第14章：投資判断のワークショップ](./chapters/part2_techstocks/14_investment_workshop.md)

---

## ✍️ **[ChatGPTテンプレート集](./templates/)｜Prompt Templates**

以下のテンプレートを**ChatGPTに貼り付けて**、**分析・比較・判断に活用**できます：

| **ファイル名** | **用途** |
|----------------|----------|
| [01_prompt_sector_selection.md](./templates/01_prompt_sector_selection.md) | 注目セクター選定用 |
| [02_prompt_etf_lookup.md](./templates/02_prompt_etf_lookup.md) | ETF構成企業の逆引き |
| [03_prompt_stock_analysis.md](./templates/03_prompt_stock_analysis.md) | 銘柄分析テンプレート |
| [04_prompt_stock_compare.md](./templates/04_prompt_stock_compare.md) | 複数銘柄の比較分析 |
| [05_prompt_custom_list.md](./templates/05_prompt_custom_list.md) | 自作銘柄リスト構築 |
| [06_prompt_investment_judgment.md](./templates/06_prompt_investment_judgment.md) | 投資判断ワークショップ用 |
| [07_prompt_fundamentals_analysis.md](./templates/07_prompt_fundamentals_analysis.md) | 財務指標（PBR・ROE等）分析 |
| [08_prompt_pbr1x_response.md](./templates/08_prompt_pbr1x_response.md) | PBR1倍割れ企業の是正策分析 |
| [09_prompt_us_macro_analysis.md](./templates/09_prompt_us_macro_analysis.md) | 米国金利・インフレ・FRB政策の分析 |
| [10_prompt_macro_vs_stocks.md](./templates/10_prompt_macro_vs_stocks.md) | マクロ指標と株式セクターの相関分析 |

---

## 🛠 **対象読者｜Target Audience**

- **投資初心者**（NISA・ETF・積立投資から始めたい方）  
- **テクノロジー分野に関心がある個人投資家**  
- **ChatGPTを使って投資を可視化・自動化したい方**  
- **教育・社内研修で教材として使いたい方**（MITライセンス対応）

---

## 🧾 **今後の拡張予定｜Planned Enhancements**

- ✅ **四季報スタイルの企業要約テンプレート**
- ✅ **ESG／コーポレートガバナンス視点の導入**
- ✅ **年1回のリバランス支援テンプレート（GPT記録＋可視化）**
- ✅ **教育用スライド資料（社内研修・講義用）**
- ✅ **コンテンツ構造マップ（PDF／画像）とGitHub Pages整備**

---

## 🔗 **関連プロジェクトとの連携｜Project Ecosystem**

この教材は以下のプロジェクトと**連携・発展可能**です：

- [**SamizoGPT / Project Design Hub**](https://github.com/Samizo-AITL/SamizoGPT)：GPT活用とプロジェクト設計テンプレート集  
- [**Edusemi-Plus**](https://github.com/Samizo-AITL/Edusemi-Plus)：地政学・企業戦略から見た半導体投資分析教材  
- [**Rekiden**](https://github.com/Samizo-AITL/Rekiden)：戦略的意思決定とシナリオ設計力育成教材（歴史SLG型）

---

## 👤 **執筆者情報 | Author**

| 📌 項目 / Item | 内容 / Details |
|------|------|
| **氏名 / Name** | 三溝 真一（Shinichi Samizo） |
| **学歴 / Education** | 信州大学大学院 電気電子工学 修了 |
| **経歴 / Career** | 元 セイコーエプソン株式会社 技術者（1997年〜） |
| **経験領域 / Expertise** | 半導体デバイス（ロジック・メモリ・高耐圧混載）<br>インクジェット薄膜ピエゾアクチュエータ<br>PrecisionCoreプリントヘッド製品化・BOM管理・ISO教育 |
| **連絡先 / Contact** | 💻 [GitHub](https://samizo-aitl.github.io/) |

---

## 📄 **ライセンス / License**

- **JP:** 本教材は [**MIT License**](https://opensource.org/licenses/MIT) に基づき、**教育・非営利での再利用・編集・派生**を歓迎します。  
- **EN:** Licensed under **[MIT License](https://opensource.org/licenses/MIT)**. Free to **reuse, modify, and fork** for education/non-profit.

> **JP:** 記述は執筆者の調査・思考に基づきます。｜**EN:** Opinions are those of the author.

---

## 💬 **フィードバック | Feedback**
> 改善提案や議論はGitHub Discussionsからお願いします。  
> *Propose improvements or start discussions via GitHub Discussions.*

[![💬 GitHub Discussions](https://img.shields.io/badge/💬%20GitHub-Discussions-brightgreen?logo=github)](https://github.com/Samizo-AITL/AssetPortfolio-StartGuide/discussions)

