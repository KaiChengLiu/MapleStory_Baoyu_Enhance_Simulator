## 新楓之谷_寶玉屬性加成強化模擬器

### 簡介
本專案模擬 **寶玉屬性加成強化系統 (0～10級)** 的成功、失敗與重置機率，並統計 **所需楓幣花費**。  
使用者可設定 **目標級別**，並指定模擬次數，獲取強化過程的成本分佈。

本模擬器包含：
- **基於強化機率的級別提升模擬**
- **多次模擬並計算 25%、50%、75% 百分位數及平均花費**
- **繪製各級別的花費分佈直方圖**

---

### 依賴環境
請確保你的 Python 環境已安裝以下套件：
- `numpy`
- `matplotlib`
- `statistics`

若尚未安裝，可執行以下命令：
```bash
pip install numpy matplotlib
```

---

### 檔案結構
```
📺 enhence_simulation/
│-- 📄 enhance_simulation.ipynb  # Jupyter Notebook (強化模擬程式)
│-- 📄 README.md                 # 本文件
```

---

### 使用方法

#### 1. 在 Jupyter Notebook 內執行
你可以使用 Jupyter Notebook **(推薦)** 來運行此模擬器：
```bash
jupyter notebook enhance_simulation.ipynb
```

#### 2. 設定模擬目標
在 Notebook 內修改 **目標級別** (`target_level`) 及 **模擬次數** (`num_sims`)：
```python
test_levels = [7, 8, 9, 10]  # 需要測試的目標級別
num_sims = 100000  # 每個目標級別的模擬次數
```

#### 3. 執行強化模擬
運行 Notebook，模擬器將：
- **計算各級花費的 25%、50%、75% 百分位數及平均值**
- **繪製強化花費分佈直方圖**

---

###  版本記錄
- **v1.0**: 初版發布，支援 0～10 級強化模擬，並提供統計分析與圖表顯示。

---

###  聯絡方式
- 
如有任何問題或建議，請與我聯絡！

