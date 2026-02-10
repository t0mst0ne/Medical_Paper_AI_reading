# 研究參數、定義與來源彙整 (基於 Supplement s1.pdf)

以下根據Supplement s1.pdf的內容，整理出研究中使用的關鍵參數、定義以及數據來源。

## 1. 數據來源 (Cohorts)

| 來源 | 全名 | 描述與收案標準 |
| :--- | :--- | :--- |
| **ADNI** | Alzheimer’s Disease Neuroimaging Initiative | **2004年啟動的公私合作項目**。<br>納入標準：Aβ+ (類澱粉蛋白陽性，由ADNI協議定義)，且至少有一次 Tau-PET 或 Fujirebio p-tau217 數據，以及至少一次 CDR-SB 分數。 |
| **Penn-ADRC** | Penn Alzheimer’s Disease Research Center | **賓州大學的縱向觀察研究**。<br>納入標準：血漿 p-tau217 和 Aβ42 數據可用 (Fujirebio Lumipulse平台)。<br>Aβ+ 定義為 **p-tau217/Aβ42 > 0.0055**。<br>至少有一次 CDR-SB 分數。 |
| **Penn-ATM** | Penn Antiamyloid Therapy Monitoring | **接受抗類澱粉蛋白治療的臨床世代**。<br>對象：MCI 或 AD 失智患者，正在接受治療。<br>數據點：治療前 (baseline) 的 p-tau217、MMSE 和 DSRS。 |

---

## 2. 生物標記與影像參數 (Parameters)

### A. Tau 蛋白負荷 (Tau Burden)
*   **Tau-PET (Global Tau-MaX)**:
    *   **定義**: 一個衡量全局 Tau 蛋白**強度 (magnitude)** 和 **範圍 (extent)** 的綜合指標。
    *   **計算方式**:
        1.  將 SUVR 轉換為 Tau 病理指數 (TPI)。
        2.  設定閾值：TPI > 2 SD (高於非病理分佈 2 個標準差) 的區域視為 Tau+。
        3.  將 Tau+ 區域的 TPI 乘以相對區域大小並加總。
    *   **Tau+ 切點**: **Tau-MaX > 3.31** (基於 Aβ- 認知正常者的 97.5 百分位數)。
    *   **來源**: 18F-flortaucipir PET 影像，ADNI 檔案庫。

*   **血漿 p-tau217**:
    *   **平台**: **Fujirebio Lumipulse G1200** 分析儀。
    *   **用途**: 作為 Tau 負荷量的替代指標。
    *   **Tau+ 切點**: **p-tau217 > 0.3175 pg/mL** (基於 Youden Index，用於識別 Tau-MaX > 3.31 的個體)。
    *   **Aβ+ 切點**: **p-tau217/Aβ42 > 0.0055** (代表 95% 敏感度閾值)。

### B. 神經影像 (MRI)
*   **TDP-43 影像特徵**:
    *   **參數**: **ERC/PHC Ratio** (內嗅皮層厚度 / 海馬旁回厚度)。
    *   **定義**: 此比值降低與 TDP-43 病理有關 (LATE signature)。
*   **內側顳葉 (MTL) 分割**:
    *   **工具**: **T1-ASHS** 和 **CRASHS** pipeline。
    *   **區域 (ROIs)**: 前海馬 (aH)、後海馬 (pH)、杏仁核 (Amygdala)、內嗅皮層 (ERC)、Brodmann Area 35 & 36、海馬旁回 (PHC)。

## 3. 臨床評估參數 (Clinical Assessment)

*   **CDR-SB (Clinical Dementia Rating Sum of Boxes)**:
    *   主要臨床結果指標。
    *   在 Penn-ATM 世代中因無 CDR-SB，使用以下公式從 DSRS 和 MMSE 推算 (**Crosswalk formula**):
        $$ \text{CDR-SB} = 7.50 + 0.23 \times \text{DSRS} - 0.26 \times \text{MMSE} $$
        ($R^2 = 0.83$)

*   **ETOA (Estimated Tau Onset Age)**:
    *   **定義**: 估計個體達到 Tau 陽性 (Tau+) 的年齡。
    *   **計算**: 使用 **SILA (Sampled-Iterative Local Approximation)** 方法，將個體置於共同的生物時間軸上。

## 4. 統計定義 (Statistical Definitions)

*   **不配對 (Mismatch) 分組定義**:
    *   使用線性回歸：$ \text{CDR-SB} \sim \text{Tau} + \text{Age} + \text{Sex} + \text{Education} $
    *   計算 **標準化殘差 (Standardized Residuals, SR)**:
        *   **典型組 (Canonical)**: $-0.6 \le \text{SR} \le 0.6$
        *   **韌性組 (Resilient)**: $\text{SR} < -0.6$ (症狀比預期輕)
        *   **脆弱組 (Vulnerable)**: $\text{SR} > 0.6$ (症狀比預期重)

*   **校正多重比較**:
    *   **FDR (False Discovery Rate)**: 用於全腦皮層 ROI 分析。
    *   **FWE (Family-Wise Error)** with TFCE: 用於 MTL 頂點分析 (vertex-wise)。
