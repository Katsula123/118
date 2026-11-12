---
title: 對流性吸附理論（Convection-Dependent Adsorption, CDA）
type: concept
tags: [electroplating, cda, additives, peg, sps, chloride]
date: 2026-11-12
updated: 2026-11-12
sources: [RAW/000101 強迫對流效應對微米級填孔電鍍銅製程的影響.pdf]
status: active
---

# 對流性吸附理論（Convection-Dependent Adsorption, CDA）

**對流性吸附機構（Convection-Dependent Adsorption, CDA）** 是由國內學者竇維平教授（W.P. Dow）等人於 2005 年提出之微米級填孔電鍍銅理論，用以解釋強迫對流如何透過調控**氯離子（$\text{Cl}^-$）**分佈來決定陰極表面的局部抑制或加速行為。

---

## 1. 核心物理與電化學機制

1. **抑制劑（PEG）的吸附條件**：聚乙二醇（PEG）必須藉由 $\text{Cl}^-$ 與一價/二價銅離子形成錯合物作為橋樑，才能穩定吸附於陰極銅表面並阻擋銅沉積。
2. **氯離子的電性排斥與脫附**：$\text{Cl}^-$ 帶負電，與陰極表面之間存在強烈的靜電排斥力，因此在無對流或弱對流區域（例如高縱橫比盲孔底部），$\text{Cl}^-$ 容易發生脫附，表面形成約 $30\,\mu\text{m}$ 的擴散層。
3. **強迫對流的關鍵角色**：透過空氣攪拌或噴流循環產生的**強迫對流**，提供 $\text{Cl}^-$ 足夠的動能抵抗陰極排斥力並輸送至孔外表面與孔口：
   - **高對流區（孔外表面與下游孔口）**：$\text{Cl}^-$ 濃度高 $\rightarrow$ 有利 PEG 吸附 $\rightarrow$ **抑制銅沉積**。
   - **弱對流區（盲孔底部）**：$\text{Cl}^-$ 難以到達，PEG 抑制失效，而加速劑（SPS）得以進行協同作用 $\rightarrow$ **孔底加速沉積（Bottom-up Filling）**。

---

## 2. 評估指標與理論演進定位

- **相對沉積厚度率（Relative Deposition Thickness, RDT）**：定義為孔底沉積厚度與孔外表面沉積厚度之比值（$H_2 / H_1$）。在 CDA 機構中，提高空氣攪拌流量（如由 $0.5\text{ L/h}$ 升至 $2.5\text{ L/h}$）可使 RDT 由 $2.4$ 顯著提升至 $4.4$。
- **與其他填孔理論之差異**：
  - **ACD 理論（West et al., 2000）** 與 **CEAC 理論（Moffat & Josell, 2001）**：主要針對 IC 次微米／奈米級特徵建立，著重添加劑擴散吸附與幾何曲率演變，未納入強迫對流效應。
  - **CDA 理論**：特別適用於特徵尺寸較大的 **PCB 微米級盲孔**，補足了流體動力學與添加劑協同作用的耦合視角（見 [[paper-2011-hsu-forced-convection-microvia]]）。

---

## 3. 相關頁面
- [[paper-2011-hsu-forced-convection-microvia]]
- [[concept-microvia-copper-electroplating-mass-transfer]]
