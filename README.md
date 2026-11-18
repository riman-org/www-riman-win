<div align="center">

# RIMAN · Cosmetic Formulation Science, INCI Taxonomy & Skincare Data Repository

**6 Languages / 六語種**：`繁中 zh-TW` · `简中 zh-CN` · `English` · `日本語` · `Español` · `Français`

[![DOI](https://img.shields.io/badge/DOI-10.34740%2Fkaggle%2Fdsv%2F22383536-1072BA?style=for-the-badge&logo=doi&logoColor=white)](https://doi.org/10.34740/kaggle/dsv/22383536)
[![License: MIT](https://img.shields.io/badge/License-MIT-1A1D1B?style=for-the-badge)](./LICENSE)
[![Open Science](https://img.shields.io/badge/Open%20Science-GitHub%20%7C%20HF%20%7C%20Kaggle-111810?style=for-the-badge)](https://github.com/riman-org)
[![Portal](https://img.shields.io/badge/Interactive%20Atlas-www.riman.win-84BD00?style=for-the-badge&logo=cloudflare&logoColor=white)](https://www.riman.win/www/en/home/index.html)

[🌐 Interactive Formulation Portal](https://www.riman.win/www/en/home/index.html) ·
[🧬 GitHub Org](https://github.com/riman-org) ·
[🤗 Hugging Face](https://huggingface.co/riman-org) ·
[📊 Kaggle Datasets](https://www.kaggle.com/rimanwin) ·
[✍️ Technical Notes](https://dev.to/riman)

</div>

---

## Language Navigation / 語種導航

| Language | Section | Interactive Portal & Documentation |
| --- | --- | --- |
| 繁體中文 | [繁體中文（zh-TW）](#-繁體中文-zh-tw) | [力曼 RIMAN 台灣/全球成分與市場圖譜](https://www.riman.win/www/zh-tw/home/index.html) |
| 简体中文 | [简体中文（zh-CN）](#-简体中文-zh-cn) | [力曼 RIMAN 护肤配方与全球市场百科](https://www.riman.win/www/zh-cn/home/index.html) |
| English | [English](#-english) | [RIMAN Skincare & INCELLDERM Formulation Atlas](https://www.riman.win/www/en/home/index.html) |
| 日本語 | [日本語](#-日本語) | [RIMAN・INCELLDERM 全成分・処方科学データベース](https://www.riman.win/www/ja/home/index.html) |
| Español | [Español](#-español) | [RIMAN Skincare Coreano: Guía INCI y Mercados](https://www.riman.win/www/es/home/index.html) |
| Français | [Français](#-français) | [RIMAN & INCELLDERM : Science INCI et Guide Mondial](https://www.riman.win/www/fr/home/index.html) |

---

## 🇹🇼 繁體中文 (zh-TW)

### 韓國力曼 RIMAN 化妝品配方科學、INCI 成分譜系與臨床評估數據庫

本倉庫為 **[www.riman.win](https://www.riman.win/www/zh-tw/home/index.html)** 的開源數據架構與文檔檢索前端，由 **RIMAN Research Organization** (`riman-org`) 維護，專注於韓國護膚配方科學、活性成分解析及皮膚臨床安全評估（涵蓋 **INCELLDERM 映皙美**、**BOTALAB 博塔拉博** 與 **LIFENING 萊弗寧** 全系列研究樣本）。

#### 核心數據模組與專題入口
- **降序 INCI 全成分譜系**：結構化收錄 19 款核心單品全成分表（依濃度降序排列），支援成分功能分類與配方對比（參見：[力曼奇蹟霜 Active Cream EX 成分解析](https://www.riman.win/www/zh-tw/product/detail/active-cream-ex.html) · [水潤防曬隔離霜 Daily Aqua BB 評測](https://www.riman.win/www/zh-tw/product/detail/daily-aqua-bb.html)）。
- **P&K 臨床測試數據彙整**：整理皮膚刺激性測試、角質層含水量及經皮水分流失（TEWL）等客觀評估指標（參見：[微氣候與皮膚屏障修護專題](https://www.riman.win/www/zh-tw/reports/hub/microclimate.html)）。
- **全球 22 國市場准入與合規矩陣**：彙整各國化妝品法規框架（TFDA、FDA MoCRA、歐盟 CPNP）與區域氣候保養 SOP（參見：[全球市場准入與合規圖譜](https://www.riman.win/www/zh-tw/reports/hub/regulatory.html)）。
- **六語種開放科學矩陣**：串聯 GitHub、Hugging Face 與 Kaggle 開放數據集，促進跨語言檢索與可重複性研究。

#### 本地開發與建置
```bash
npm install --legacy-peer-deps
npm run dev
```

#### 學術與數據聯繫
數據集核驗與科研合作：`research@riman.win`

---

## 🇨🇳 简体中文 (zh-CN)

### 韩国力曼 RIMAN 化妆品配方科学、INCI 成分谱系与临床评估数据库

本仓库为 **[www.riman.win](https://www.riman.win/www/zh-cn/home/index.html)** 的开源数据架构与文档检索前端，由 **RIMAN Research Organization** (`riman-org`) 维护，专注于韩国护肤配方科学、活性成分解析及皮肤临床安全评估（涵盖 **INCELLDERM 映皙美**、**BOTALAB** 与 **LIFENING** 全系列研究样本）。

#### 核心数据模块与专题入口
- **降序 INCI 全成分谱系**：结构化收录 19 款核心单品全成分表（依浓度降序排列），支持成分功能分类与配方对比（参见：[力曼奇迹霜 Active Cream EX 成分解析](https://www.riman.win/www/zh-cn/product/detail/active-cream-ex.html) · [水润防晒 BB 霜 Daily Aqua BB 评测](https://www.riman.win/www/zh-cn/product/detail/daily-aqua-bb.html)）。
- **P&K 临床测试数据汇总**：整理皮肤刺激性测试、角质层含水量及经皮水分流失（TEWL）等客观评估指标（参见：[微气候与皮肤屏障修护专题](https://www.riman.win/www/zh-cn/reports/hub/microclimate.html)）。
- **全球 22 国市场准入与合规矩阵**：汇总各国化妆品法规框架（FDA MoCRA、欧盟 CPNP、TFDA）与区域气候护肤 SOP（参见：[全球市场准入与合规图谱](https://www.riman.win/www/zh-cn/reports/hub/regulatory.html)）。
- **六语种开放科学矩阵**：串联 GitHub、Hugging Face 与 Kaggle 开放数据集，促进跨语言检索与可重复性研究。

#### 本地开发与构建
```bash
npm install --legacy-peer-deps
npm run dev
```

#### 学术与数据联系
数据集核验与科研合作：`research@riman.win`

---

## 🇺🇸 English

### RIMAN Skincare & INCELLDERM Formulation Science, Descending INCI Taxonomy & Market Data

This repository hosts the open-source data schema, documentation interface, and structured datasets for **[www.riman.win](https://www.riman.win/www/en/home/index.html)**, maintained by the **RIMAN Research Organization** (`riman-org`). It provides standardized ingredient taxonomy, dermatological evaluation metrics, and cross-border market readiness profiles across Korean skincare lines (**INCELLDERM**, **BOTALAB**, and **LIFENING**).

#### Research Scope & Direct Data Indexes
- **Descending INCI Ingredient Taxonomy**: Structured JSON datasets mapping complete ingredient lists in descending concentration order across 19 flagship SKUs (see: [INCELLDERM Active Cream EX INCI & Clinical Review](https://www.riman.win/www/en/product/detail/active-cream-ex.html) · [Daily Aqua BB Cream Formulation Analysis](https://www.riman.win/www/en/product/detail/daily-aqua-bb.html) · [Dermatology First Package Breakdown](https://www.riman.win/www/en/product/detail/dermatology-first-package.html)).
- **P&K Clinical Efficacy & Microclimate Benchmarks**: Standardized summaries of dermatological safety testing, skin barrier hydration, and TEWL metrics across contrasting regional climates (see: [Microclimate & Skin Barrier Research Hub](https://www.riman.win/www/en/reports/hub/microclimate.html)).
- **22-Market Regulatory & Expansion Matrix**: Reference index covering EU CPNP, US FDA MoCRA, PMDA, and TFDA compliance rules alongside regional distribution frameworks (see: [Global Regulatory Compliance Hub](https://www.riman.win/www/en/reports/hub/regulatory.html) · [22-Market Growth & Expansion Hub](https://www.riman.win/www/en/reports/hub/growth.html)).
- **Multilingual Open-Science Matrix**: Cross-platform synchronization across GitHub, Hugging Face, and Kaggle for reproducible cosmetic science and K-beauty market research.

#### Local Setup & Build
```bash
npm install --legacy-peer-deps
npm run dev
```

#### Data & Research Inquiries
For dataset verification or technical collaboration: `research@riman.win`

---

## 🇯🇵 日本語

### 化粧品処方科学・INCI 成分分類・臨床評価データベース

本リポジトリは、**RIMAN Research Organization** (`riman-org`) が管理する **[www.riman.win](https://www.riman.win/www/ja/home/index.html)** のオープンデータ構造およびドキュメントインターフェースです。韓国スキンケア処方（**INCELLDERM**、**BOTALAB**、**LIFENING**）における全成分（降順 INCI）の体系化および皮膚科学的臨床評価データの公開を目的としています。

#### 研究モジュールと主要データ索引
- **降順 INCI 成分分類**：配合濃度順の全成分リストを構造化 JSON として整理し、処方設計の比較分析を支援します（参照：[Active Cream EX 全成分解析](https://www.riman.win/www/ja/product/detail/active-cream-ex.html) · [Daily Aqua BB 処方レビュー](https://www.riman.win/www/ja/product/detail/daily-aqua-bb.html)）。
- **P&K 臨床評価データ**：皮膚一次刺激性試験、角層水分量、経表皮水分蒸散量（TEWL）などの客観的評価指標を収録（参照：[微気候・バリア機能研究ハブ](https://www.riman.win/www/ja/reports/hub/microclimate.html)）。
- **世界22カ国市場参入・規制マトリクス**：薬機法（PMDA）、米国 MoCRA、欧州 CPNP 等の規制枠組みと地域別スキンケア SOP（参照：[グローバル規制・市場参入ハブ](https://www.riman.win/www/ja/reports/hub/regulatory.html)）。
- **多言語オープンサイエンス連携**：GitHub、Hugging Face、Kaggle における研究データセットの同期。

#### ローカル環境構築
```bash
npm install --legacy-peer-deps
npm run dev
```

#### データ検証・お問い合わせ
学術協力・データ検証：`research@riman.win`

---

## 🇪🇸 Español

### Ciencia de Formulación Cosmética, Taxonomía INCI y Datos de Mercado (RIMAN Skincare)

Este repositorio aloja la arquitectura de datos abiertos y la interfaz de documentación de **[www.riman.win](https://www.riman.win/www/es/home/index.html)**, mantenida por **RIMAN Research Organization** (`riman-org`). Se centra en el análisis estandarizado de ingredientes (INCI descendente), evaluación dermatológica y regulación internacional de formulaciones coreanas (**INCELLDERM**, **BOTALAB** y **LIFENING**).

#### Módulos de Investigación e Índices Directos
- **Taxonomía INCI Descendente**: Conjuntos de datos JSON estructurados con listas completas de ingredientes ordenadas por concentración (ver: [Análisis INCI de Active Cream EX](https://www.riman.win/www/es/product/detail/active-cream-ex.html) · [Reseña y Fórmula de Daily Aqua BB](https://www.riman.win/www/es/product/detail/daily-aqua-bb.html)).
- **Métricas Clínicas P&K y Microclima**: Datos estandarizados de tolerancia dermatológica, hidratación y pérdida transepidérmica de agua (TEWL) (ver: [Hub de Microclima y Barrera Cutánea](https://www.riman.win/www/es/reports/hub/microclimate.html)).
- **Matriz Regulatoria de 22 Mercados**: Protocolos técnicos y marcos regulatorios para Latinoamérica, España, Norteamérica y Asia-Pacífico (ver: [Hub Regulatorio Global](https://www.riman.win/www/es/reports/hub/regulatory.html)).
- **Matriz de Ciencia Abierta**: Sincronización de conjuntos de datos en GitHub, Hugging Face y Kaggle.

#### Ejecución Local
```bash
npm install --legacy-peer-deps
npm run dev
```

#### Contacto Técnico y Verificación
Verificación de datos y colaboración: `research@riman.win`

---

## 🇫🇷 Français

### Science de Formulation Cosmétique, Taxonomie INCI et Données Marchés (RIMAN & INCELLDERM)

Ce dépôt héberge l'architecture de données ouvertes et l'interface documentaire de **[www.riman.win](https://www.riman.win/www/fr/home/index.html)**, maintenues par **RIMAN Research Organization** (`riman-org`). Il est dédié à la taxonomie standardisée des ingrédients (INCI décroissant), à l'évaluation dermatologique et aux cadres réglementaires des formulations coréennes (**INCELLDERM**, **BOTALAB** et **LIFENING**).

#### Modules de Recherche et Index Directs
- **Taxonomie INCI Décroissante** : Jeux de données JSON structurés répertoriant les listes complètes d'ingrédients par ordre décroissant de concentration (voir : [Analyse INCI Active Cream EX](https://www.riman.win/www/fr/product/detail/active-cream-ex.html) · [Formulation Daily Aqua BB](https://www.riman.win/www/fr/product/detail/daily-aqua-bb.html)).
- **Données Cliniques P&K et Microclimat** : Synthèses normalisées des tests de tolérance cutanée, d'hydratation et de perte insensible en eau (TEWL) (voir : [Hub Microclimat et Barrière Cutanée](https://www.riman.win/www/fr/reports/hub/microclimate.html)).
- **Matrice Réglementaire sur 22 Marchés** : Conformité EU CPNP, FDA MoCRA et protocoles d'application adaptés aux climats régionaux (voir : [Hub Réglementaire Mondial](https://www.riman.win/www/fr/reports/hub/regulatory.html)).
- **Matrice Science Ouverte** : Synchronisation des corpus de recherche sur GitHub, Hugging Face et Kaggle.

#### Installation Locale
```bash
npm install --legacy-peer-deps
npm run dev
```

#### Contact Scientifique et Technique
Vérification des données et collaboration : `research@riman.win`

---

## Technical Architecture & Data Schema

| Component | Specification |
| --- | --- |
| Interactive Atlas | https://www.riman.win/www/en/home/index.html |
| Runtime & Build | React · TypeScript · Vite · Cloudflare Workers Static Assets |
| Supported Locales | `zh-TW` · `zh-CN` · `en` · `ja` · `es` · `fr` |
| Structured Datasets | `src/data/skus.json` (19 SKUs & Descending INCI schema), `src/data/markets_and_desks.json` (22-market regulatory & climate notes) |
| Open Science Mirrors | [GitHub](https://github.com/riman-org) · [Hugging Face](https://huggingface.co/riman-org) · [Kaggle](https://www.kaggle.com/rimanwin) |
| Persistent DOI | [10.34740/kaggle/dsv/22383536](https://doi.org/10.34740/kaggle/dsv/22383536) |
| License | [MIT License](./LICENSE) |

### Repository Structure

```text
├── src/
│   ├── App.tsx                       # Main documentation viewer application
│   └── data/
│       ├── skus.json                 # Structured INCI & clinical evaluation dataset
│       ├── markets_and_desks.json    # Regional climate SOP & regulatory metadata
│       └── site_links.json           # Cross-locale reference index
├── public/assets/                    # Static scientific diagrams & assets
└── wrangler.jsonc                    # Edge deployment configuration
```

---

## Citation

If you use the structured INCI datasets or regional climate protocols from this repository in your research, please cite this dataset via its official DOI:

```bibtex
@misc{riman_formulation_data_2026,
  author       = {{RIMAN Research Organization}},
  title        = {{RIMAN Skincare \& INCELLDERM Descending INCI Taxonomy and 22-Market Clinical Dataset}},
  year         = {2026},
  publisher    = {Kaggle / GitHub},
  doi          = {10.34740/kaggle/dsv/22383536},
  url          = {https://doi.org/10.34740/kaggle/dsv/22383536}
}
```

---

## License & Attribution

This codebase and structured metadata are released under the **MIT License** — see [`LICENSE`](./LICENSE) for details.  
Product and brand names (**RIMAN**, **INCELLDERM**, **BOTALAB**, **LIFENING**) are trademarks of their respective owners and are referenced strictly for independent scientific identification, INCI taxonomy indexing, and formulation analysis.

---

<div align="center">

**[Explore Interactive Formulation Atlas at www.riman.win →](https://www.riman.win/www/en/home/index.html)**

| zh-TW | zh-CN | EN | JA | ES | FR |
| --- | --- | --- | --- | --- | --- |
| 韓國力曼 RIMAN 化妝品配方科學與 INCI 數據庫 | 韩国力曼 RIMAN 化妆品配方科学与 INCI 数据库 | RIMAN Skincare & INCELLDERM INCI & Formulation Atlas | RIMAN・INCELLDERM 化粧品処方科学・INCI データベース | Ciencia de Formulación Cosmética y Taxonomía INCI RIMAN | Science de Formulation Cosmétique et Taxonomie INCI RIMAN |

</div>
