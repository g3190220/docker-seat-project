# 座位管理系統

- 設計發想：每次學生考試都需重新隨機排定梅花座，若學生數過多，這項工作變得耗時耗力
- 使用者：助教、教授
- 系統功能：只需設定教室和學生名單，即可取得排好的隨機座位表。
- 網頁預覽：
  ![image](https://user-images.githubusercontent.com/32484169/204429909-edf841c7-6266-444b-a444-d277d9eb79e2.png)

### 1. 設定每間教室：row、col、走道、預設容納數

![image](https://user-images.githubusercontent.com/32484169/204430229-8c9bb12b-d89e-4739-95a8-31724c84e125.png)

### 2. 上傳學生清單：固定格式

- 需為.csv 檔
- 欄位：name、id

### 3. 前端送出後，後端會回傳設定教室分別座位表(excel)之壓縮檔，前端自動下載

# 使用技術：
- 前端：Vue.js、Vuetify
- 後端：FastAPI
- 部署：Docker (基於Docker-Compose 集成部署前後端服務)
