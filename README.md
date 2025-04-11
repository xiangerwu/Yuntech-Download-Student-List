# 📥 eClass 學生名單下載器（油猴腳本）

這是一個 Tampermonkey 油猴腳本，能讓你在 [eClass 雲科大數位學習平台](https://eclass.yuntech.edu.tw/) 中，一鍵匯出課程中的學生名單為 `.csv` 檔案，方便期中/期末考監考、點名或行政彙整作業。

---

## 🚀 功能特色

- ✅ 自動抓取左側 `.left-container` 名單資料
- ✅ 輸出格式為 `姓名,學號`，並支援 Excel 正確開啟（UTF-8 with BOM）
- ✅ 插入原生扁平化按鈕，與 eClass 按鈕風格一致
- ✅ 一鍵點擊即可下載 `student_list.csv` 檔案

---

## 🧑‍🏫 使用情境

- 教師 / 助教需要快速整理課程名單
- 不想手動一筆一筆複製學生資料
- 不需後台權限也能快速導出

---

## 🛠 安裝方式

1. 安裝 [Tampermonkey](https://www.tampermonkey.net/) 擴充功能（支援 Chrome / Firefox / Edge）
2. 新增腳本，匯入 `main.js` 內容
3. 前往 `https://eclass.yuntech.edu.tw` 頁面，即可看到「📥 下載名單」按鈕

---

## 📄 匯出檔案格式

| 欄位  | 說明       |
|-------|------------|
| 姓名   | 學號   |
| 中文全名| 例如 A123456 |

檔名：`student_list.csv`

---

## 💡 畫面範例

按鈕會顯示在「新增」、「設定課程角色權限」旁邊：

```text
+ 新增   ⚙ 設定課程角色權限   ⬇ 下載名單
```

---

## 📂 專案結構

```text
.
├── script.js      # Tampermonkey 腳本主體
└── README.md      # 說明文件（本檔案）
```

---

## 📜 License

MIT License — 自由使用與修改，請保留原作者資訊。
