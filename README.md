# 🧑‍💻 AI & CS Portfolio（作品集總覽）

## 📑 專案目錄
1. ⚖️ 法規檢索與諮詢 AI 助理(專題)
2. 🤖 Python 機器人期末報告
3. 🧠 大型語言模型問答聊天機器人建構
4. ⚡ 以效能為導向的客製化聊天機器人
5. 🌱 環境感測器與 LINE Bot 輔助通報系統
6. 💰 個人財務管理系統
7. ☁️ GCP 上建立 LINE Bot 伺服器
8. 🔬 雲端與邊緣運算應用（LeNet / ResNet / EfficientDet 合集）
9. 🎨 使用者經驗設計 - 介面易用性分析
10. 🤖 自建 NLP 聊天機器人（LINE + GCP 部署）

## 📖 簡介
本作品集整合了多個人工智慧與電腦科學領域的專案，涵蓋 **AI 模型訓練、雲端應用、UX 分析** 等主題。  
所有專案均來自課程實作或自主開發，完整展現資料處理、程式設計與系統整合能力。  
---

## 📂 專案清單

### 1. ⚖️ 法規檢索與諮詢 AI 助理(專題)  
- **Repo**：[law-ai-assistant](https://github.com/fgx2060/linebot-law-rag.git)  
- **簡介**：基於 **LINE Bot + AnythingLLM + Ollama** 的本地部署法規檢索與諮詢助理，支援自然語言查詢全國法規資料庫，回覆包含條號、段落與出處。

### 2. 🤖 Python 機器人期末報告  
- **Repo**：[python-chatbot-robot](https://github.com/fgx2060/python-robot-control.git)  
- **簡介**：使用 Python 控制 mBot2 智慧機器人，整合感測器驅動與自動化行為。  

### 3. 🧠 大型語言模型問答聊天機器人建構  
- **Repo**：[llm-qa-chatbot](https://github.com/fgx2060/llm-qa-chatbot.git)  
- **簡介**：基於 LLM 的 QA 聊天機器人，整合 LINE Bot，具多輪短期記憶、角色扮演、（可選）簡繁轉換。*（不含 RAG）*。  

### 4. ⚡ 以效能為導向的客製化聊天機器人  
- **Repo**：[efficient-chatbot](https://github.com/fgx2060/performance-oriented-chatbot.git)  
- **簡介**：LangChain + 向量檢索（RAG）+ LoRA/QLoRA，在資源受限（如 Colab CPU）下優化推論效能與回覆品質。  

### 5. 🌱 環境感測器與 LINE Bot 輔助通報系統  
- **Repo**：[iot-linebot-alert](https://github.com/fgx2060/sensor-data-linebot.git)  
- **簡介**：Arduino 端蒐集環境數據（.ino），Python 端接收與判斷，透過 LINE Bot 即時推播警示（含 AI 解釋模式）。 

### 6. 💰 個人財務管理系統  
- **Repo**：[personal-finance-system](https://github.com/fgx2060/personal-finance-system.git)  
- **簡介**：Python Tkinter 桌面應用，提供收支記錄、每月儲蓄目標、月報建議與 Matplotlib 視覺化。（主程式 `15.py`）

### 7. ☁️ GCP 上建立 LINE Bot 伺服器  
- **Repo**：[gcp-linebot-server](https://github.com/fgx2060/gcp-linebot-server.git)  
- **簡介**：- **簡介**：在 GCP VM 部署 Flask + LINE Webhook，支援 ngrok/外部 IP 綁定與即時回覆。

### 8. 🔬 雲端運算與邊緣運算應用（EfficientDet / LeNet / ResNet 合集）  
- **Repo**：[cloud-edge-inference](https://github.com/fgx2060/edge-model-inference.git)  
- **簡介**：影像分類與目標偵測模型的訓練與 Edge 部署流程彙整（含對照與簡易 Benchmark）。 

### 9. 🎨 使用者經驗設計 - 介面易用性分析  
- **Repo**：[ux-usability-analysis](https://github.com/fgx2060/ux-usability-analysis.git)  
- **簡介**：以 SUS、任務滿意度與 Product Reaction Card 評估介面易用性，彙整改進清單（顯示密碼、下載按鈕、日期跳轉）。

### 10. 🤖 自建 NLP 聊天機器人（LINE + GCP 部署）  
- **Repo**：[nlp-linebot-gcp](https://github.com/fgx2060/nlp-linebot-gcp.git)  
- **簡介**：自建 GPT 模型工作流（資料清理 → 詞典 → 訓練 → 測試 → LINE/GCP 部署）。`notebooks/change.ipynb` 用於簡體轉繁體與前期資料處理。

---

## 📊 技能展現
- **AI/ML**：LoRA/QLoRA、語意檢索（RAG）、CNN/ResNet/EfficientDet、PyTorch / Transformers  
- **系統開發**：Flask + LINE Bot、Tkinter GUI、Arduino 感測器整合  
- **雲端與部署**：GCP VM、ngrok、基本 CI/CD 規劃  
- **UX 研究**：SUS、任務滿意度、Reaction Card、可用性研究流程與報告撰寫

---

## 📖 文件與報告
每個專案均附有：  
- **README.md**：專案簡介、功能特色與安裝方式  
- **PDF / PPTX**：課程期末報告或簡報檔  
  
