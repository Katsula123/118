---
title: 知識庫研究領域總覽
type: overview
tags: [overview, research-map, llm, electroplating]
date: 2026-11-12
updated: 2026-11-12
sources: [RAW/000101 強迫對流效應對微米級填孔電鍍銅製程的影響.pdf]
status: active
---

# 研究領域總覽（Overview）

本頁是整個研究知識庫的最高層導航地圖，隨著新論文與技術報告的 **Ingest**，AI Agent 會持續補充各研究主軸的代表性文獻、關鍵突破與未解問題。

---

## 領域 A：微電子製程與電鍍銅數值模擬（Microvia Electroplating & CFD）

### 核心機制與數值方法
- **理論基礎**：[[concept-cda-convection-dependent-adsorption|對流性吸附理論（CDA）]]、[[concept-microvia-copper-electroplating-mass-transfer|微米級盲孔電鍍銅質量傳遞與流體動力學]]
- **代表文獻**：
  - [[paper-2011-hsu-forced-convection-microvia]]：以 COMSOL 耦合 Navier-Stokes、Nernst-Planck 與 Butler-Volmer 方程式，驗證強迫對流可提升孔底離子通量，但受限於縱橫比 $1.2$ 門檻；側壁傾斜 $5^\circ$ 反而降低孔底通量 $5\text{--}10\%$。

---

## 領域 B：大型語言模型研究（LLM Research）

### 1. 基礎架構與預訓練（Architecture & Pre-training）
- **關注議題**：Transformer 變體（GQA、MLA、MoE）、長上下文、Scaling Laws、合成資料。
- **已收錄頁面**：*（待補充）*

### 2. 後訓練與對齊（Post-training & Alignment）
- **關注議題**：SFT、RLHF（PPO）、DPO、可驗證獎勵強化學習（RLVR / GRPO）。
- **已收錄頁面**：*（待補充）*

### 3. 推理與測試時計算（Reasoning & Test-time Compute）
- **關注議題**：Chain-of-Thought (CoT)、過程獎勵模型（PRM）、樹狀搜尋、自我驗證。
- **已收錄頁面**：*（待補充）*

### 4. AI Agents 與工具使用（Agents & Tool Use）
- **關注議題**：Agentic Workflows、Harness Engineering、Multi-Agent、MCP / Tool Use。
- **已收錄頁面**：*（待補充）*

### 5. RAG、記憶與知識工程（RAG & Knowledge Systems）
- **關注議題**：混合檢索、GraphRAG、長期記憶架構、LLM Wiki。
- **已收錄頁面**：*（待補充）*
