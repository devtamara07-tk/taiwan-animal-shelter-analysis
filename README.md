# 🐾 台灣動物收容所分析
## Taiwan Animal Shelter & Adoption Analysis

> **核心問題 / Main Question:** 高雄市的流浪寵物有得到足夠的幫助嗎？  
> Are abandoned pets in Kaohsiung getting enough support?

---

## 📊 專案簡介 / Project Overview

本專案透過 Python 分析台灣動物收容所系統，結合多個政府開放資料來源，探討高雄市流浪動物的支援現況。

This project analyzes Taiwan's animal shelter system using multiple government open data sources, focusing on Kaohsiung City.

---

## 🌐 Live Presentation

👉 [Click here to view the presentation](https://devtamara07-tk.github.io/taiwan-animal-shelter-analysis/presentation_taiwan_animals_v4.html)

---

## 📡 資料來源 / Data Sources

| 資料集 | 說明 | 格式 |
|--------|------|------|
| 動物認領養 API | 每日更新的全國動物認養資料 | Live JSON |
| 高雄市動物醫院一覽表 | 319間獸醫院資料 | Static CSV |
| SEGIS 高雄市各區人口統計 | 2024年各行政區人口 | JSON |
| 台灣行政區域邊界 | GeoJSON地理邊界資料 | GeoJSON |

---

## 🔍 主要發現 / Key Findings

- 🏆 高雄市平均等待天數 **291天**，遠低於全國平均 **1,020天**
- 💙 高雄是台灣僅有的 **3個零安樂死城市**之一
- 🚨 收容所容量已達 **90%以上**，街頭估計有 **10,000+** 隻流浪動物
- 🗺️ **8個行政區**完全沒有獸醫服務
- 🐾 25天內有 **124隻動物**找到新家（平均每天4.6隻）

---

## 🛠️ 使用工具 / Tools Used

```python
Python | Pandas | Matplotlib | Seaborn | Scipy
Folium | GeoPandas | Requests | Pillow
```

---

## 📁 檔案說明 / Repository Files

| 檔案 | 說明 |
|------|------|
| `*.py` | 主要分析程式碼 |
| `*.pptx` | 簡報檔案 |
| `*.html` | 自動播放簡報影片 |
| `*.csv` | 2026年4月23日資料快照 |

---

## 🌟 未來展望 / Future Work

- 建立自動化每日資料排程
- 開發即時認養儀表板 (Streamlit)
- 將分析擴展至全台灣所有城市
- 為所有收容所動物拍攝專業大頭照 📸
- 推動混種犬成為台灣官方認可犬種 🐕

---

## 💙 致謝 / Acknowledgement

本專案的靈感來自布丁——我14歲的貓咪。  
*Inspired by Puddin, my 14-year-old cat. 🐱*

**作者 / Author:** Tamara 候旦妮  
**日期 / Date:** May 2026  
**課程 / Course:** 就業認證直播-Python程式資料分析_021
