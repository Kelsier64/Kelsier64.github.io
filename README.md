# Kelsier64.github.io
Welcome to my portfolio.
嗨！我是Kelsier(凱西爾)一位覺得什麼有趣就開發什麼的高中生
- **聯絡方式**: evan.du.dog@gmail.com
- github: [https://github.com/Kelsier64](https://)


## 關於我
我是興趣導向的個人開發者，擅長python的原型開發以及api或網站應用，喜歡研究最新技術
### 技能與經驗

#### 後端開發  
  - 熟悉python的 Django 和 Flask 框架，搭配SQL資料庫，有 API 與 Web 開發經驗
  
#### 前端開發  
  - 掌握 HTML、CSS、JavaScript（但系統學過的是過時的jQuery），常用 Jinja2

#### 網路爬蟲  
  - 使用 Python 的 Selenium 開發動態爬蟲工具

#### AI API 整合  
  - 長期使用 OpenAI SDK 開發，擅長將 AI 功能整合到不同應用場景中
  - 有時也會直接用api request

#### 物聯網開發
  - 具備 Arduino / ESP32 cam/ raspberry pi zero2 的開發經驗

#### 伺服器部署與管理  
  - 長期使用 WSL（Windows 上的 Linux 環境）開發專案
  - 擁有個人 Linux 伺服器，用於遊戲伺服器、網站托管、模型微調/推理/訓練
  - 略懂雲端伺服器的應用與部署

#### 版本控制  
  - 熟練使用 Git 和 GitHub 進行版本管理，適應團隊協作的工作流

#### Markdown 文檔
  - 習慣使用 hackmd 記錄開發過程

#### 資訊安全
  - 掌握基礎資安技術，會在專案中實作防護措施  
  - 曾參加AIS3J，獲得優秀個人/帶領小組獲得專題第一名

#### Docker
  - 略懂 Docker 技術，能進行基本容器化部署

---

## llm世界引擎
給llm獨立的記憶系統，並且提供高自由度，讓他們以文本交互方式模擬生活

### 功能
- llm角色跟系統ai回報自己的動作，由系統ai決定角色對世界的影響，所以整個世界都是可以讓ai修改的，實現超高自由度
- ai角色記憶系統，主要是正在做的事，短期記憶，長期記憶
- ai角色之間可以互動
- 每個物件/角色都有自己獨立的描述
- 座標+狀態系統方便世界引擎套用到任何遊戲介面上
- 多環境分區加載

### 技術棧
- asyncio
- openai sdk

### 展示
![Screenshot 2024-10-20 013350](https://hackmd.io/_uploads/SyM1lsJC1g.png)
這邊只展示了一點點，但可以看到有
- 人物互動 他們講話
- 物件互動 有人跑去讀書
- 環境切換 有人離開房間跑去廚房做飯

github: [https://github.com/Kelsier64/ai_text_game](https://)

## 聲音克隆(小明劍魔迷因)discord語音生成機器人
小明劍魔當紅梗產生器，只要加入discord就能快速得到ai克隆的聲音，不管是聊天還是玩遊戲時都很好用
### 功能
- 指令快速使用克隆語音模型tts
- 加入通話或是直接下載語音檔案
- 自動配對經典關鍵字並自動合成語音
- 多線程快速推理模型
### 技術棧
- discord.py
- gpt-sovits微調/推理tts模型
### 展示
- youtube: [https://youtu.be/2vUtZnVIaI0](https://)
- github: [https://github.com/Kelsier64/dc_voice_bot](https://)


## 訂單管理網站
功能完整的訂單管理網站
### 功能
- 登入+身份驗證系統
- 區分管理者/使用者/使用者類別訂單管理
- 使用者可以下單/查看同類別使用者訂單
- 管理者可以查看所有類別使用者訂單 或是刪除
- 管理者可以增刪改查使用者
- 管理者可以增刪改查商品
- 訂單自動統計圖表功能
- 測試中功能：ai助理 可以幫忙查詢商品/訂單 以及下單
### 技術棧
- django web框架/class_base_views
- sqlite資料庫
### 展示

- youtube: [https://youtu.be/ff_TkNODYkY?si=4aIZm42Sju-ZE9Wu](https://)
- github: [https://github.com/Kelsier64/order_manage_web](https://)

## 家教AIapi整合discord機器人
自動且方便利用reasoning models快速生成題目詳解的ai家教
### 功能
- 上傳一頁題目圖片自動**一題一題**生成詳解
- 自動根據題型改變prompt
- 處理題組/跨頁題組等多種複雜情況
- 有discord端跟api端可以同時用
### 技術棧
- openai sdk

### 展示
- github: [https://github.com/Kelsier64/order_manage_web](https://)

## ai拼圖網站
美術課自由發揮作業，我覺得效果不錯
### 功能
- 輸入提示詞生成拼圖
- 點擊拼圖可以查看提示詞
- 輸入密碼可以看原圖
- 簡單但完整的前後端
### 技術棧
- openai sdk:GPT Image
- flask
### 展示
![1000031424](https://hackmd.io/_uploads/rks4cXSgge.png)










