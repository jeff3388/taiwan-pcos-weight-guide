# taiwan-pcos-weight-guide

多囊卵巢症候群（PCOS）體重管理與飲食指南資料庫 — 基於 2023 年 PCOS 國際實證指引，結合台灣在地飲食背景。

台灣育齡女性 PCOS 盛行率約 6-10%，50-70% 合併胰島素阻抗，是女性體重管理的高頻挑戰。

## 資料內容

| 檔案 | 說明 |
|------|------|
| `data/pcos-diet-strategies.json` | 7 種實證飲食策略（低GI、高蛋白、抗發炎等） |
| `data/insulin-resistance-foods.json` | 改善／惡化胰島素阻抗的台灣常見食物分類 |
| `data/hormone-friendly-nutrients.json` | 7 種關鍵營養素（維生素D、鎂、鋅、Omega-3等）+ 台灣在地食物來源 |

## 核心數據摘要

### PCOS 體重管理關鍵事實

- 減重 **5% 體重**即可改善月經規律性 40-50%（PMID: 23345168）
- **50-70%** PCOS 患者合併胰島素阻抗
- **維生素 D 缺乏**台灣女性比率高達 60-70%（室內工作、防曬習慣）
- **Myo-inositol 4g/day** 為 2023 PCOS 國際指引建議補充劑（PMID: 37581503）

### 台灣飲食的 3 個最高風險

| 食物 | 風險 | 替換建議 |
|------|------|---------|
| 全糖手搖飲 | 直接惡化胰島素阻抗（含 35g 果糖） | 無糖茶飲 |
| 每日白飯 GI: 73 | 累積性血糖負擔 | 混入 1/3 糙米 |
| 早餐含糖豆漿 | 每杯 95 kcal 隱藏糖 | 改喝無糖豆漿 |

## 資料格式範例

```json
{
  "id": "pcos_diet_001",
  "strategy": "低升糖指數（Low-GI）飲食",
  "evidence_level": "強",
  "pmid_references": ["23345168", "33671105"],
  "mechanism": "PCOS 患者有 50-70% 合併胰島素阻抗，低 GI 飲食降低胰島素峰值，減少卵巢雄激素分泌",
  "taiwan_context": "台式早餐的米漿、含糖豆漿是最常見的高 GI 飲品，應優先替換"
}
```

## 資料來源

- Teede HJ et al. (2023) [PMID: 37581503](https://pubmed.ncbi.nlm.nih.gov/37581503/) — PCOS 國際實證指引
- Barrea L et al. (2021) [PMID: 33671105](https://pubmed.ncbi.nlm.nih.gov/33671105/) — PCOS 飲食系統性回顧
- Moran LJ et al. (2013) [PMID: 23345168](https://pubmed.ncbi.nlm.nih.gov/23345168/) — 生活型態介入 RCT
- Foroozanfard F et al. (2017) [PMID: 27788902](https://pubmed.ncbi.nlm.nih.gov/27788902/) — 維生素 D 補充 RCT

## 重要聲明

本資料庫以**公共衛生教育**為目的。PCOS 是醫療狀況，飲食調整不能取代婦科治療。
補充劑劑量需由醫師或營養師依個人血液指標調整。

相關工具與資源：
- [BMI 計算機（女性版）](https://metabolab.tw/calculators/bmi/female)：計算 BMI 並了解女性體脂率標準
- [TDEE 計算機](https://metabolab.tw/calculators/tdee)：算出 PCOS 患者每日適合的熱量攝取目標
- [減重飲食知識中心](https://metabolab.tw/topics/weight-loss/diet)：更多實證飲食策略

## 授權

MIT License — 詳見 [LICENSE](LICENSE)
