## title: 微米級盲孔電鍍銅質量傳遞與流體動力學
type: concept
tags: \[mass-transfer, navier-stokes, nernst-planck, butler-volmer, microvia\]
date: 2026-11-12
updated: 2026-11-12
sources: \[RAW/000101 強迫對流效應對微米級填孔電鍍銅製程的影響.pdf\]
status: active

# 微米級盲孔電鍍銅質量傳遞與流體動力學

在微米級盲孔（Microvia）的酸性硫酸銅電鍍製程中，電解液內的離子輸送與陰極表面沉積速率受流場、電場與濃度場的耦合控制。

## 1. 統御數學模型

### (1) 流場控制：不可壓縮 Navier-Stokes 方程式

描述電解液（假設為穩態不可壓縮牛頓流體）於盲孔內外的速度場 $\mathbf{u}$ 與壓力場 $p$：

$$
\rho \mathbf{u} \cdot \nabla \mathbf{u} = \nabla \cdot \left[-p\mathbf{I} + \eta \left(\nabla \mathbf{u} + (\nabla \mathbf{u})^T\right)\right] + \mathbf{B}
$$

### (2) 離子質傳：Nernst-Planck 方程式

同時涵蓋**擴散（Diffusion）**、電遷移（Electromigration）**與**對流（Convection）三種質量傳遞機制：

$$
\frac{\partial c_i}{\partial t} + \nabla \cdot \left(-D_i \nabla c_i - z_i u_{mi} F c_i \nabla V + c_i \mathbf{u}\right) = R_i
$$

### (3) 電極動力學：Butler-Volmer 方程式

描述陰極表面電流密度 $i$ 隨表面銅離子濃度 $C_{\text{Cu}^{2+}}$ 與過電位 $\eta$ 的分佈，並透過法拉第定律決定鍍層沉積速率 $M = \frac{i A}{n F \rho}$：

$$
i = \frac{C_{\text{Cu}^{2+}}}{C^0_{\text{Cu}^{2+}}} \sum z i_0 \left\{ \exp\left[-\frac{\alpha F \eta}{RT}\right] - \exp\left[\frac{(1-\alpha)F\eta}{RT}\right] \right\}
$$

## 2. 幾何與流場對質傳的關鍵影響（來自 \[\[paper-2011-hsu-forced-convection-microvia\]\]）

* **縱橫比閾值（Aspect Ratio** $\approx 1.2$**）**：當盲孔縱橫比超過 $1.2$ 時，流體慣性力無法克服孔壁黏滯阻力，孔口產生的渦流無法穿透至孔底，孔底離子補充退化為自然擴散與電遷移主導。

* **渦流非對稱衝擊**：水平流經盲孔開口時，下游側壁承受正向衝擊而具有較高的 $\text{Cu}^{2+}$（高出 $15\text{--}23\%$）與 $\text{Cl}^-$（高出 $2$ 倍以上）通量。

* **側壁傾角效應**：在直徑 $60\text{--}120\,\mu\text{m}$ 尺度下，側壁向外傾斜 $5^\circ$（$95^\circ$）反而會改變渦流導向並使孔底 $\text{Cu}^{2+}$ 與 $\text{Cl}^-$ 通量下降 $5\text{--}10\%$。

## 3. 相關頁面

* \[\[paper-2011-hsu-forced-convection-microvia\]\]

* \[\[concept-cda-convection-dependent-adsorption\]\]